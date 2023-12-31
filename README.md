# Printf Project in C - Alx group project (Solo participant) 

## Overview

This is a group project to create your own `printf` function in the C programming language. In this README, you'll find essential information and guidelines to successfully complete this project.

## Table of Contents

- [Background Context](#background-context)
- [Resources](#resources)
- [Requirements](#requirements)
- [Compilation](#compilation)
- [Tasks](#Tasks)
- [Contributors](#contributors)

## Background Context

For this project, you will be implementing your own version of the `printf` function. You should have an understanding of various concepts, including group projects, pair programming, flowcharts, technical writing, and the `printf` function itself.

### Resources

Before you start, make sure to read or watch the following resources:

- [Secrets of printf](https://www.cypress.com/file/54761/download)
- [Group Projects concept page](#) (Don't forget to read this)
- [Flowcharts concept page](#)
- `man` or `help` command:
  - [printf(3)](https://manpages.ubuntu.com/manpages/focal/man3/printf.3.html)

### Requirements

#### General

- You can use the following editors: `vi`, `vim`, or `emacs`.
- All your C files will be compiled on Ubuntu 20.04 LTS using `gcc` with the options `-Wall -Werror -Wextra -pedantic -std=gnu89`.
- All your C files should end with a new line.
- A `README.md` file at the root of the project folder is mandatory.
- Your code should follow the Betty style guidelines and will be checked using `betty-style.pl` and `betty-doc.pl`.
- You are not allowed to use global variables.
- Each file should contain no more than 5 functions.
- The prototypes of all your functions should be included in your header file named `main.h`.
- Don't forget to push your header file to your repository.
- All your header files should be include guarded.
- You will not be provided with the `_putchar` function for this project.

#### GitHub

- There should be one project repository per group. Other members should not fork or clone the project to ensure only one team member has the repository in their GitHub account; otherwise, you risk scoring 0%.

#### Authorized Functions and Macros

- `write` (man 2 write)
- `malloc` (man 3 malloc)
- `free` (man 3 free)
- `va_start` (man 3 va_start)
- `va_end` (man 3 va_end)
- `va_copy` (man 3 va_copy)
- `va_arg` (man 3 va_arg)

## Compilation

The code will be compiled using the following command:

$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c

## Tasks

### 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
mandatory
Write a function that produces output according to a format.

Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
- c
- s
- %
You don’t have to reproduce the buffer handling of the C library printf function
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

### 1. Education is when you read the fine print. Experience is what you get if you don't
mandatory
Handle the following conversion specifiers:
- d
- i
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

### 2. With a face like mine, I do better in print
Handle the following custom conversion specifiers:
b: the unsigned int argument is converted to binary

### 3. What one has not experienced, one will never understand in print
Handle the following conversion specifiers:
- u
- o
- x
- X
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

### 4. Nothing in fine print is ever good news
Use a local buffer of 1024 chars in order to call write as little as possible.

### 5. My weakness is wearing too much leopard print
Handle the following custom conversion specifier:

S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

### 6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier: 
- p
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

### 7. The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:
- +
- space
- #

### 8. Sarcasm is lost in print
Handle the following length modifiers for non-custom conversion specifiers:
- l
- h
- Conversion specifiers to handle: d, i, u, o, x, X

### 9. Print some money and give it to us for the rain forests
Handle the field width for non-custom conversion specifiers.

### 10. The negative is the equivalent of the composer's score, and the print the performance
Handle the precision for non-custom conversion specifiers.

### 11. It's depressing when you're still around and your albums are out of print
Handle the 0 flag character for non-custom conversion specifiers.

### 12. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
Handle the - flag character for non-custom conversion specifiers.

### 13. Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:
- r : prints the reversed string

### 14. The flood of print has turned reading into a process of gulping rather than savoring
Handle the following custom conversion specifier
- R: prints the rot13'ed string

### 15. *
All the above options work well together.

## Contributors

### 1. Moses Adegoke [@DevPrudence](https://github.com/DevPrudence)
