# Simple Calculator

## Overview

This is a simple console-based calculator program written in C++. It takes two numbers as input from the user and performs basic arithmetic operations such as addition, subtraction, multiplication, and division based on the user's choice.

## Features

- Supports four arithmetic operations: `+`, `-`, `*`, `/`
- Handles division by zero with a prompt for a valid divisor
- Uses a `switch` statement for operation selection
- Provides a user-friendly interface for input and output

## How to Use

1. Compile the program using a C++ compiler (e.g., g++):
   ```sh
   g++ calculator.cpp -o calculator
   ```
2. Run the executable:
   ```sh
   ./calculator
   ```
3. Follow the on-screen prompts:
   - Enter the first number
   - Enter the second number
   - Choose an arithmetic operation (`+`, `-`, `*`, `/`)
4. The program will display the result.

## Code Explanation

- The program prompts the user to enter two numbers.
- It then asks for the desired arithmetic operation.
- A `switch` statement is used to determine the operation and perform the calculation.
- If division by zero is attempted, the program repeatedly asks for a valid divisor.
- The result is displayed accordingly.

## Example Usage

```
Enter the first number:
5
Enter the second number:
2
Enter the operation you want to perform (+,-,*,/):
+
The sum of given numbers is: 7
```

## Improvements

- Add support for floating-point numbers.
- Implement a loop for continuous calculations.
- Improve user input validation.

## Author

Ali Haider


