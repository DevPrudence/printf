# Printf Project in C

## Overview

This is a group project to create your own `printf` function in the C programming language. In this README, you'll find essential information and guidelines to successfully complete this project.

## Table of Contents

- [Background Context](#background-context)
- [Resources](#resources)
- [Requirements](#requirements)
- [Compilation](#compilation)

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
