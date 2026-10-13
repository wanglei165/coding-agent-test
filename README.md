# Binary Search

A small Java command-line program that searches a sorted array of integers.

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
java -cp src Main <element1> <element2> ... <target>
```

For example:

```sh
java -cp src Main 1 2 3 4 5 3
```

Output:

```text
Result index: 2
```