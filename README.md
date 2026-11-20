# Binary Search

A small Java command-line program that searches a sorted array of integers for a
target value using binary search.

## Run

Compile the program from the repository root:

```sh
javac src/Main.java
```

Pass the array elements followed by the target value:

```sh
java -cp src Main 1 2 3 4 5 3
```

The program prints the index of the target, or `-1` if it is not found. The
array elements must be provided in ascending order.