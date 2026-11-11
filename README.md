# Java Arrays Example (for-each Loop)

A small Java program that creates an array of integers and prints every element with an enhanced `for` loop (for-each).

## What It Demonstrates

```java
int[] marks = {10, 12, 13, 15, 17, 19, 20};

for (int w : marks) {
    System.out.println(w);
}
```

- Declaring and initializing an array with values
- Looping through every element with `for (type variable : array)`, with no index needed

## How It Works

1. `marks` holds 7 integers.
2. On each pass, `w` takes the next value from the array.
3. The loop ends after the last element.

## Output

```
10
12
13
15
17
19
20
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac Arrays.java
java Arrays
```

## Tip

The class is named `Arrays`, which is also the name of Java's built-in `java.util.Arrays` utility class. This program works fine, but if you later need `java.util.Arrays` in the same file, a different class name such as `ArrayDemo` avoids confusion.

## Project Structure

```
.
├── Arrays.java
└── README.md
```

## Next Steps

- Add up all the values in the loop
- Use a regular `for` loop with `marks.length` and compare
- Find the largest value in the array
