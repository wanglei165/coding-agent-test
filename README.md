# Binary Search Demo

A small Java command-line program that searches a sorted array of integers using
binary search.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root:

```sh
mkdir -p out
javac -d out src/Main.java
```

## Run

Pass the array elements in ascending order, followed by the target value:

```sh
java -cp out Main 1 2 3 4 5 3
```

The program prints the index of the target, or `-1` if it is not found. In the
example above, the output is:

```text
Result index: 2
```

The current implementation does not check the final remaining candidate, so it
may return `-1` when the target is at that position.
