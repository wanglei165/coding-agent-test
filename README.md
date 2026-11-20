# Binary Search

A small Java command-line program that searches a sorted array of integers for a
target value using binary search.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root, compile the source into an `out` directory:

```sh
mkdir -p out
javac -d out src/Main.java
```

## Run

Pass the array elements in ascending order, followed by the target value:

```sh
java -cp out Main 1 2 3 4 5 3
```

The program prints the target's zero-based index, or `-1` if it is not found.
