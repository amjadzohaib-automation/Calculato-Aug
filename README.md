# Java Calculator

## Description

This is a simple calculator program written in Java. The program takes two numbers from the user and allows the user to perform a basic mathematical operation.

The program uses the Java `Scanner` class to receive input from the user.

## Features

The calculator supports the following operations:

- Addition
- Subtraction
- Multiplication
- Division
- Prevents division by zero
- Displays an error message if the user selects an invalid option

## How It Works

1. The program asks the user to enter the first number.
2. The user enters the second number.
3. The program displays four operation choices:
   - `1` for Addition
   - `2` for Subtraction
   - `3` for Multiplication
   - `4` for Division
4. The user selects an operation.
5. The calculator performs the calculation and displays the result.

## Example

```text
Enter the first number
10

Enter the second number
5

Choose an operation
1. for Addition
2. for Subtraction
3. for Multiplication
4. for Division

1

Result: 15.0
```

## Division by Zero

The program checks if the second number is zero before performing division.

For example:

```text
Enter the first number
10

Enter the second number
0

Choose an operation
4

Error: Division by Zero is not allowed
```

## Technologies Used

- Java
- Scanner Class
- If-Else Statements
- Eclipse IDE

## Author

Zohaib Amjad
