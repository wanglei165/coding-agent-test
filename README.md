# Binary Search Example

A small Java program that searches a sorted integer array for a target value
using binary search.

## Requirements

- Java Development Kit (JDK)

## Build and run

From the repository root, compile the program:

```sh
javac src/Main.java
```

Pass the array elements followed by the target value when running the program.
The array elements should be in ascending order.

```sh
java -cp src Main 1 2 3 4 5 3
```

The final argument (`3`) is the target; the preceding arguments form the array.
The example prints:

```text
Result index: 2
```

If fewer than two arguments are provided, the program prints usage information.
