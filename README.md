# Binary Search Demo

A small Java command-line program that searches a sorted array of integers for a
target value and prints its index.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root, run:

```sh
javac src/Main.java
```

## Run

Pass the array elements in ascending order, followed by the target value:

```sh
java -cp src Main 1 2 3 4 5 3
```

The final argument (`3`) is the target. The program prints:

```text
Result index: 2
```

If the target is not found, the program prints `Result index: -1`.