# C-Tutorial

Collection of learning meterials

## Overview

- C is a general-purposee, middle-level programming language created by Dennis Ritchie at the Bell Laboratories in 1972.
- C is strongly associated with UNIX, as it was developed to write the UNIX operating system.

## Why C?

- C is amoung the most popular programming languages.
  TIOBE Index for December 2022

1. Python
2. C
3. C++
4. Java
5. C#

- It has largely been superseded in that domain by higher-level languages, such as C++, Objective-C, C#, and Java.

- C is very fast, compared to other programming languages, like Java and Python

- C language is platform independent.

## C Versions

- K&R C : Original (1978)
- ANSI C or C89: American National Standards Institute (ANSI)
- ISO C90 or C90: International Organization for Standardization
- C95, C99, C11: ANSI standard for the C programming language
- C17: The most recent standard. C18 standard provided only clarifications to C11 and introduced no new language features.
- C2x: Next standard

## C vs. C++

- C++ was developed as an extension of C, and both languages have almost the same syntax.
- The main difference between C and C++ is that C++ support classes and objects, while C does not.

## IDE

Popular IDE's include Code::Blocks, Eclipse, Visual Studio, and CodeLite.

### Visual Studio

- Install Visual Studio IDE
- Right click on the .c file and click “Properties”. Then expand the C/C++ menu, go to “Advanced”, loop for the “Compile As” section and select from the drop down menu “Compile as C Code (/TC)”

### Code::Blocks

- http://www.codeblocks.org/downloads/binaries
- codeblocks-20.03mingw-setup.exe

### Running C online

- https://www.codechef.com/ide

### Setup for VSCODE

Code Setting

- Setup Mingw
- Install & Setup MSYS2
- Setup MSYS2 MINGW64
- Setup path
- Setup cmd

VSCODE Setting

- Install C/C++ Extension
- Install Code Runner Extension
- File > Preference > Setting > Extension > Run code configuration > Check Run In Terminal
- Terminal > Configure Default Build Task

## Building Blocks

### Comments

- // oneline comment
- /\* \*/ multiline comment
- ; semi colon is used to signify the end of a line.

## Variables and Types

- Each variable must have a defined type
- It’s good practise to make meaningful name
- Cannot be a single digit
- Cannot contain special characters (!”£$%^&\*) etc.
- Global variable: variable definition outside the main function (can be accessed anywhere)

### Integer

- Integer: real numbers

### String

- String: a array of characters
- "\n" is a special character that stands for a newline.

### Booleans

- Booleans: true (1) or false (0)

### Float/Double

- Float/Double: decimal values
- Floating point precision: Floats allows for a higher level of accuracy of a value

### Void

- Void: no value / not type

## Keywords

| Keywords | Description       | Example                     |
| -------- | ----------------- | --------------------------- |
| int      | integer variable  | int integerValue = 3;       |
| float    | decimal variable  | float decimalValue = 3.0f;  |
| double   | decimal readonly  | double decimalValue = 3.0f; |
| char     | string variable   | char word[] = "string";     |
| \_Bool   | variable readonly | \_Bool falseIsDetected = 0; |
| const    | readonly variable | const float pi = 3.14f;     |

### Arithmetic operations

| Symbol | Description | Example               |
| ------ | ----------- | --------------------- |
| +      | plus        | int result = 1 + 2;   |
| -      | minus       | int result = 1 - 2;   |
| /      | devide      | float result = 1 / 2; |
| \*     | multiply    | int result = 1 \* 2;  |
| %      | modulus     | float result = 1 % 2; |

### Conditionals

| Symbol          | Description              | Example                                                 |
| --------------- | ------------------------ | ------------------------------------------------------- |
| >               | greater than             | if (value > 5)                                          |
| >=              | greater than or equal to | if (value >= 5)                                         |
| <               | less than                | if (value < 5)                                          |
| <=              | less than or equal to    | if (value <= 5)                                         |
| ==              | equal                    | if (value == 5)                                         |
| !=              | not equal                | if (value != 5)                                         |
| if() {}         | if condition             | if (value > 5) {printf("yes");}                         |
| if() {} else {} | if else condition        | if (value > 5) {printf("yes");} \n else {printf("no");} |
