# Binary Search

A small Java command-line program that searches an integer array with binary
search.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root, run:

```sh
javac src/Main.java
```

## Run

Pass the array elements as integer arguments, followed by the target value.
The array elements must be in ascending order.

```sh
java -cp src Main 1 2 3 4 5 3
```

The program prints the result as `Result index: <index>`, where the index is
zero-based. If the target is not found, it prints `Result index: -1`.
