# Binary Search CLI

A small Java command-line program that searches an integer array for a target value.
Provide the array elements in ascending order, followed by the target.

## Compile

```sh
javac -d out src/Main.java
```

## Run

```sh
java -cp out Main 1 2 3 4 5 3
```

The program prints `Result index:` followed by the index returned by the search,
or `-1` when the target is not found.