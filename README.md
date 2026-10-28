# Number System Converter in C++

A console-based Number System Converter developed using C++ to convert decimal numbers into binary, octal, and hexadecimal number systems.

This project was created to improve my C++ programming skills and strengthen my understanding of number systems used in digital electronics and computer engineering.

## Features

- **Decimal to Binary** (Base 10 → Base 2)
- **Decimal to Octal** (Base 10 → Base 8)
- **Decimal to Hexadecimal** (Base 10 → Base 16)
- Display all conversions simultaneously
- Interactive menu using switch-case statements
- Repeated conversions without restarting the program
- Basic input validation

## Technologies Used

- **Programming Language:** C++
- **Development Environment:** Dev-C++ / Visual Studio
- **Application Type:** Console Application
- **Concepts:** Number Systems, Base Conversion, Modular Programming

## Example Output

```text
===== NUMBER SYSTEM CONVERTER =====

1. Decimal to Binary
2. Decimal to Octal
3. Decimal to Hexadecimal
4. Show All Conversions
5. Exit

Enter your choice: 4
Enter a positive decimal number: 25

Decimal: 25
Binary: 11001
Octal: 31
Hexadecimal: 19
```

## How to Run

1. Clone or download this repository.
2. Open `NumberSystemConverter.cpp` in Dev-C++ or Visual Studio.
3. Compile and run the program.
4. Select a conversion option from the menu.
5. Enter a non-negative decimal integer.
6. View the converted result in the terminal.

## C++ Concepts Practiced

- Variables and data types
- Functions and return values
- Switch-case statements
- Do-while loops
- Conditional statements
- Modulo and division operators
- String manipulation
- Basic input validation

## How It Works

The program converts decimal numbers into other number systems using repeated division.

1. Divide the decimal number by the target base.
2. Record the remainder.
3. Repeat the process until the quotient becomes zero.
4. Reverse the remainders to obtain the converted number.

For example, converting decimal 25 to binary:

```text
25 / 2 = 12  Remainder: 1
12 / 2 =  6  Remainder: 0
 6 / 2 =  3  Remainder: 0
 3 / 2 =  1  Remainder: 1
 1 / 2 =  0  Remainder: 1

Binary Result: 11001
```

## Project Motivation

As an Electrical and Electronics Engineering student interested in digital hardware design, FPGA development, and VLSI/ASIC design, I developed this project to apply fundamental programming concepts to number system conversions.

Understanding binary, octal, and hexadecimal representations is essential for digital logic, computer architecture, and hardware design.

## Future Improvements

- Binary to Decimal conversion
- Octal to Decimal conversion
- Hexadecimal to Decimal conversion
- Direct conversion between different bases
- Improved input validation
- Support for larger numbers and additional number formats

## Author

Developed as part of my C++ programming and digital electronics learning journey.
