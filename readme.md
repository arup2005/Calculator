# Calculator using C Program

## This is a Lab Assignment
- NAME - Arup Debnath
- DEPARTMENT - BCA
- SEM - 2nd
- ROLL - 30001223052
- REGISTRATION - 233001010526

## Description
- This is a simple calculator program written in C that performs basic arithmetic operations: addition, subtraction, multiplication, and division. The program prompts the user to enter an operator and two operands, then performs the corresponding calculation and displays the result.

## How to Use
- Compile the Program: Use a C compiler to compile the program. For example, you can use gcc:
gcc -o calculator calculator.c

### Run the Program: Execute the compiled program:
- ./calculator

### Input: Follow the prompts to enter an operator (+, -, *, /) and two operands (numbers).
Example:
- Enter an operator (+, -, *, /): +
- Enter two operands: 5 3

### Output: The program will display the result of the operation.
Example:
- 5.00 + 3.00 = 8.00

## Code Explanation
- Header File: The program includes the standard input-output library:
#### #include <stdio.h>

- Main Function: The main function contains the core logic of the program.

- Switch Statement: The program uses a switch statement to handle different operators and perform the corresponding arithmetic operation.

- Error Handling: The program checks for division by zero and invalid operators, displaying appropriate error messages.

## Notes
- Ensure that the input values are valid numbers and the operator is one of the specified characters (+, -, *, /).
- The program handles floating-point numbers for more precise calculations.
