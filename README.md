# Binary Search Demo

A small Java command-line program that searches a sorted list of integers for a
target value and prints its index.

## Requirements

- Java Development Kit (JDK)

## Build and run

From the repository root, compile the program:

```sh
mkdir -p out
javac -d out src/Main.java
```

Pass the sorted integer values followed by the target to search for:

```sh
java -cp out Main 1 2 3 4 5 3
```

Output:

```text
Result index: 2
```

The index is zero-based. The program prints `-1` when the target is not found.
