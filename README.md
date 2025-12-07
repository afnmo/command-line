# Argument Sum Program

This is a simple C program that demonstrates how to handle **command-line arguments**.  
It prints all the arguments passed to the program and calculates the sum of integers provided.


---

## Features
- Prints `"Hello, World!"` when executed.
- Displays the number of arguments passed.
- Lists all arguments with their index.
- Calculates the sum of integers passed as arguments.
- Handles the case when no integers are provided.

---

## Compilation
Use `gcc` to compile the program:

```bash
gcc main.c -o main
```

---
##  Usage
Run the program with integers as arguments:

```bash
./main 10 20 30
```

---
## Examples

Example 1: With integers
```bash
./main 5 15 25
```

Output:

```Code
Hello, World!
Number of arguments: 4
argv[0] = ./main
argv[1] = 5
argv[2] = 15
argv[3] = 25
Sum = 45
```

Example 2: No integers provided
```bash
./main
```
Output:

```code
Hello, World!
Number of arguments: 1
argv[0] = ./main
No numbers provided. Please pass integers to calculate the sum.
```
