# Q2_FA1_Molave_Barbaso_ModularCalculator
# Modular Calculator Mini-Program

## Project Information
- **Name:** Cindy P. Barbaso
- **Section:** Molave
- **Activity:** Q2_FA1 – Creating a Modular Calculator Mini-Program
- **Programming Language:** Python

## Description
The Modular Calculator Mini-Program is a simple Python program that performs four basic arithmetic operations: addition, subtraction, multiplication, and division. It uses separate functions to make the code organized, readable, and reusable.

## Features
- Accepts two numbers from the user.
- Allows the user to choose an arithmetic operation.
- Uses separate functions for each operation.
- Uses parameters and arguments to pass values.
- Returns and displays the calculated result.
- Handles division by zero.
- Validates numerical input and detects invalid operation choices.

## Functions Used

| Function | Purpose | Return Value |
|---|---|---|
| `add_numbers(num1, num2)` | Adds two numbers | Sum |
| `subtract_numbers(num1, num2)` | Subtracts the second number from the first | Difference |
| `multiply_numbers(num1, num2)` | Multiplies two numbers | Product |
| `divide_numbers(num1, num2)` | Divides the first number by the second | Quotient or error message |

## How to Run
1. Open the Python source code file.
2. Run the program using Python or Google Colab.
3. Enter the first number.
4. Enter the second number.
5. Choose an operation from the menu:
   - `1` – Addition
   - `2` – Subtraction
   - `3` – Multiplication
   - `4` – Division
6. View the result displayed by the program.

## Sample Output

```text
Enter first number: 10
Enter second number: 5

Choose operation:
1 - Addition
2 - Subtraction
3 - Multiplication
4 - Division
Enter choice: 1
Result: 15.0
```

## Program Versions

### Version 1 – Initial Program
The first version implements the four basic arithmetic operations using separate functions, parameters, arguments, and return values.

### Version 2 – Improved Program
The second version improves readability by adding comments and function descriptions. It also includes input validation and error handling for division by zero and invalid numerical input.

## Concepts Applied
- Functions
- Parameters and arguments
- Return values
- Conditional statements
- User input and output
- Exception handling
- Code readability and modular programming
- Version control using GitHub

## Purpose of the Project
This project demonstrates how modular programming can divide a program into smaller functions, making it easier to understand, test, reuse, and maintain.
