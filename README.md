
# ft_printf

**ft_printf** is a custom implementation of the standard C printf() function, developed as part of the curriculum at Hive Helsinki. This project demonstrates my understanding of variadic functions, string formatting, and output in C.

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

## Prerequisites
- A C compiler (e.g., `gcc` or `clang`)  
- `make`  

## Compilation
To compile **ft_printf** and create the library:
1. Clone the repository:
```
git clone git@github.com:k2matu/42-ft_printf.git ft_printf
```
2. Navigate into the ft_printf and compile the library:
```
cd ft_printf
make
cd ..
```
The compiled libftprintf.a library will be created at the root of the ft_printf repository.

## Usage

To use **ft_printf** in your own project:
1. Include the ft_printf.h header in your C source file 

#### e.g., my_program.c:
```c
#include "ft_printf.h"

int main(void) {
    ft_printf("Hello, World!\n"); // Output: Hello, World!
    return 0;
}
```
2. Compile your project with the libftprintf.a library:
```
gcc -o my_program my_program.c -L./ft_printf -lftprintf -I./ft_printf
```
3. Run your program
```
./my_program
# Output:
# Hello, World!
```
