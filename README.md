
# ft_printf

ft_printf is a custom implementation of the standard C printf() function, developed as part of the curriculum at Hive Helsinki. This project demonstrates my understanding of variadic functions, string formatting, and output in C.

Key Features Supported Conversions:
-  c : Character
- s : String
- p : Pointer address
- d or i : Signed decimal integer
- u : Unsigned decimal integer
- x : Lowercase hexadecimal
- X : Uppercase hexadecimal
- % : Percent sign

Function Prototype: 
```
int ft_printf(const char *format, ...);
```

## Installation
To compile ft_printf and create the library:
```
1. Clone the repository:
    git clone git@github.com:k2matu/ft_printf.git
2. Navigate into the directory:
    cd ft_printf
3. Compile the library using make:
    make
4. The compiled libftprintf.a library will be created at the root of the repository.
```

## Usage

To use ft_printf in your own project:
1. Include the ft_printf.h header in your project files:
```
#include "ft_printf.h"
```
2. Compile your project with the libftprintf.a library:
```
gcc -o my_program my_program.c -L. -lftprintf
```