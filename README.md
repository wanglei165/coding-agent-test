# Binary Search Demo

A small Java command-line program that searches a sorted list of integers for a
target value and prints its index.

## Requirements

- Java Development Kit (JDK)

## Compile and run

From the repository root, compile the program and pass the sorted array values
followed by the target value:

```sh
javac src/Main.java
java -cp src Main 1 2 3 4 5 3
```

The final argument is the target; all preceding arguments are the array
elements. The example prints:

```text
Result index: 2
```

If fewer than two arguments are provided, the program prints usage information.
