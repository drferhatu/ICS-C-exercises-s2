# ICS-C-exercises-s2

# Advanced C Programming Exercises (6-15)

## Exercise 6: Numbers Divisible by 3
Write a program that creates an array of numbers divisible by 3 from 100 down to 50.
```c
// Expected output: 99, 96, 93, 90, 87, 84, 81, 78, 75, 72, 69, 66, 63, 60, 57, 54, 51
// Hint: Use a for loop with appropriate step size
```

## Exercise 7: Three-Column Output
Create a program that displays three columns using a for loop (i=1 to 10):
- Column 1: i*5
- Column 2: 100-((i-1)*10+1)
- Column 3: i
```c
// Expected output format:
// 5  99  1
// 10 89  2
// 15 79  3
// etc.
```

## Exercise 8: Array Input and Statistics
Create a program that:
- Accepts 10 numbers from the user
- Displays all numbers
- Calculates and displays their sum
- Calculates and displays their average
```c
// Hint: Use an array to store the numbers
// Display results on separate lines
```

## Exercise 9: Dynamic Input with Sentinel
Create a program that:
- Accepts numbers until user enters -1
- Counts how many numbers were entered
- Calculates sum of numbers (excluding -1)
- Calculates average of numbers (excluding -1)
```c
// Hint: Use while loop with sentinel value
// Remember to exclude -1 from calculations
```

## Exercise 10: Multiplication Table
Create a program that generates a 10x10 multiplication table for numbers 1 to 10.
```c
// Expected Output:
// 1  2  3  4  5  6  7  8  9  10
// 2  4  6  8  10 12 14 16 18 20
// 3  6  9  12 15 18 21 24 27 30  
// etc.
```

## Exercise 11: X Pattern
Create a program that draws an X pattern using asterisks (*) in a 5x5 grid.
```c
// Expected Output:
// *   *
//  * * 
//   *  
//  * * 
// *   *
```

## Exercise 12: Iterative Factorial
Create a program that calculates factorial of a number (less than 50) using iteration.
```c
// Example: 5! = 5 * 4 * 3 * 2 * 1 = 120
// Include input validation
```

## Exercise 13: Recursive Factorial
Create a program that calculates factorial of a number (less than 50) using recursion.
```c
// Same as Exercise 12 but using recursive function
// Compare performance with iterative version
```

## Exercise 14: Fibonacci Series
Create a program that:
- Finds nth Fibonacci number using recursion
- Displays all Fibonacci numbers up to nth position
```c
// Example Fibonacci series: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...
// Each number is sum of two preceding numbers
```

## Exercise 15: Pattern Generator
Create a program that generates a diamond pattern using numbers:
```c
//     1
//    121
//   12321
//  1234321
// 123454321
//  1234321
//   12321
//    121
//     1
```

### Notes

- These exercises progress from basic loops and conditions to more complex concepts like recursion
- Emphasize code organization and proper indentation
- Encourage you to test edge cases
- Discuss efficiency differences between iterative and recursive solutions
- Help you understand when to use different loop types (for vs while)
- Practice debugging techniques with common errors

### Common Pitfalls
- Array indexing errors
- Infinite loops in recursive functions
- Integer overflow in factorial calculations
- Not handling edge cases
- Incorrect loop termination conditions
