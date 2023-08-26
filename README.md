# Project: Printf

This project implements a simplified version of the standard C library function `printf`. The project consists of several source files, each contributing to the functionality of the `printf` function. The goal is to provide a basic understanding of formatting and printing output in C programming.

## Author

- Author: Precious Okwukwe Amaechi [Preshengr]

## Files and Tasks

The project includes the following files and tasks:

1. **1-digit.c**: This file contains a function that prints a single digit.
2. **1-print.c**: This file contains a function that prints a character.
3. **2-number.c**: This file contains a function that prints an integer.
4. **2-print.c**: This file contains a function that prints a string.
5. **3-printf.c**: This file contains the main `printf` function implementation, which processes format specifiers and calls corresponding functions to print formatted output.
6. **README.md**: This document provides an overview of the project and its contents.
7. **_putchar.c**: This file contains a function that writes a character to the standard output.
8. **main.h**: This header file contains function prototypes and included libraries for the project.
9. **man_printf**: This is a manual page that provides information about the `printf` function and its usage.
10. **numbers.c**: This file contains functions for printing numbers with various formatting options.
11. **numbs.c**: This file contains functions related to printing numeric values.
12. **precision.c**: This file contains functions to handle precision when printing floating-point numbers.
13. **spec.c**: This file contains functions to handle different format specifiers in the `printf` function.

## Compilation

To compile the project, use the provided `main.h` header file along with the relevant source files. You can use a C compiler like `gcc`:

```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o printf
```

## Usage

Once compiled, you can use the `printf` function just like the standard C library `printf`:

```c
#include "main.h"

int main(void) {
    _printf("Hello, %s!\n", "Printf");
    _printf("This is a number: %d\n", 42);
    return (0);
}
```

## License

This project is licensed to ALX. You can find the licensing details in the source files.

Feel free to explore and modify the code to better understand how the `printf` function works and how different formatting options can be implemented in C.

For more detailed information on the project's functionality, you can refer to the source code files and comments within them.
