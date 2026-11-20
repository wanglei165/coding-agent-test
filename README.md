# Binary Search

A small Java command-line program that searches an integer array for a target value and prints its index.

## Requirements

- Java Development Kit (JDK)

## Compile and run

Compile the program:

```sh
javac -d out src/Main.java
```

Provide the array elements in ascending order, followed by the target value:

```sh
java -cp out Main 1 2 3 4 5 3
```

The final argument is the target; all preceding arguments form the array. This example prints:

```text
Result index: 2
```

The program prints `-1` when it does not find the target.
