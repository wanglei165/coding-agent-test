# Binary Search

A small Java command-line program that searches an integer array for a target value.

## Requirements

- Java Development Kit (JDK)

## Compile

From the repository root, run:

```sh
javac src/Main.java
```

## Run

Provide the array elements in ascending order, followed by the target value:

```sh
java -cp src Main 1 2 3 4 5 3
```

The final argument (`3`) is the target; the preceding arguments are the array. This example prints `Result index: 2`. The program returns `-1` when it does not find the target.

At least one array element and a target value are required. The current search implementation may skip checking the final remaining element, so some searches can return an incorrect result.