# Binary Search

A small Java command-line program that searches for an integer in a sorted
array of integers.

## Run

Compile the program:

```sh
javac -d out src/Main.java
```

Pass the array elements in ascending order, followed by the value to search
for:

```sh
java -cp out Main 1 2 3 4 5 3
```

The final argument (`3`) is the search target. The program prints its index in
the array:

```text
Result index: 2
```

If the value is not found, the program prints `Result index: -1`.
