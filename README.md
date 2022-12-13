# 42cursus-01-Printf
## :books: About the project
This project aims to recreate the behavior of printf, including its basic error handling and some of its flags. We mainly learning about variadic arguments.

## Score
  ![thumbnail_IMG_9161](https://user-images.githubusercontent.com/106436743/205688203-a9676c49-daf1-4ace-a23e-432c8af1983f.jpg)

## :warning: Mandatory  
* Your function has to handle the following conversions: `<cspdiuxX%>`
* Flags `<-O.*>` and minimum field width with all conversions

### Functions in `<ft_print_hex.c>`
* `<%x>` || `<%X>`: [ft_print_hex](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_print_hex.c) - prints a number in hexadecimal format in lowercase and uppercase

### Functions in `<ft_print_pointer.c>` (and auxiliary functions)
* `<%p>`: [ft_print_pointer](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_print_hex.c) - prints a pointer in hexadecimal format

### Functions in `<ft_print_unsig.c>` (and auxiliary functions)
* `<%u>`: [ft_print_unsig](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_print_unsig.c) - prints an unsigned

### Functions in `<ft_printf.c>`
* [ft_printf](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_printf.c) - initialization function: start/end variable argument functions where argument numbers are undefined
* [ft_format](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_printf.c) - checks each format specifier and calls as functions according to the collected format specifiers.

### Functions in `<ft_putchar.c>`
* `<%c>`: [ft_putchar](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_putchar.c) - writes a specified character to the output unit provided

### Functions in `<ft_putnbr.c>` (and auxiliary functions)
* `<%i>` || `<%d>`: [ft_putnbr](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_putnbr.c) - prints the characters representing the numbers

### Functions in `<ft_putstr.c>`
* `<%s>`: [ft_putstr](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_putstr.c) - writes the string to the given output unit

## Makefile 
* [ft_printf.h](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/ft_printf.h)
* [Makefile](https://github.com/JenniferAraujo/42cursus-01-Printf/blob/main/Makefile) 

## :computer: Compiling the project
The library is written in C language and thus needs the -cc compiler and some standard C libraries to run.

**Instruction**
1. Compiling the project

         $ make
         $ make fclean
    ![thumbnail_image2](https://user-images.githubusercontent.com/106436743/205688200-3e0f2615-7cb9-4ad6-a027-4cdbebba4220.jpg)

2. Execute your program

         $ cc ft_printf.c ft_putchar.c ft_putstr.c ft_print_unsig.c ft_print_pointer.c ft_print_hex.c ft_putnbr.c && ./a.out
    ![thumbnail_image1](https://user-images.githubusercontent.com/106436743/205688197-c9881542-d1e0-48c5-b375-0e0b0fef529f.jpg)

## :lady_beetle: Testing 

**Third-party testers used in the project**
* [Tripouille/printfTester](https://github.com/Tripouille/printfTester)

    ![thumbnail_image0](https://user-images.githubusercontent.com/106436743/205688192-4d50d956-17ca-473d-9e46-8984caa2a67b.jpg)









