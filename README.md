# Binary Search

A small Java command-line program that searches a sorted list of integers for a target value.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root, run:

```sh
mkdir -p out
javac -d out src/Main.java
```

## Run

Pass the sorted integers followed by the target value:

```sh
java -cp out Main 1 2 3 4 5 3
```

The program prints the zero-based index of the target, or `-1` if it is not found.
