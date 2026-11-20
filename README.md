# Binary Search

A small Java command-line program that searches a sorted integer array for a
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
java -cp src Main 1 2 3 4 5 4
```

The final argument is the target; all preceding arguments form the array. The
program prints a zero-based index when the target is found, or `-1` otherwise.
For the example above, the output is:

```text
Result index: 3
```
