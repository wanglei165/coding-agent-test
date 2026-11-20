# Binary Search

A small Java command-line program that searches a sorted list of integers for a
target value and prints the resulting index.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root, run:

```sh
javac src/Main.java
```

## Run

Pass the sorted integer values followed by the target value:

```sh
java -cp src Main 1 2 3 4 5 4
```

The example prints:

```text
Result index: 3
```

If the target is not found, the program prints `Result index: -1`.