# 🔍 Binary Search

A small Java command-line program that searches an ascending sequence of integers
for a target value and prints the matching index.

## 📋 Requirements

- Java Development Kit (JDK)

## 🚀 Compile and run

From the repository root:

```sh
javac src/Main.java
java -cp src Main 1 2 3 4 5 4
```

The final argument is the target; all preceding arguments are the array values.
The example prints:

```text
Result index: 3
```

⚠️ The search currently has an edge case when the search range narrows to a single
element, so it may report `-1` even when that element matches the target.