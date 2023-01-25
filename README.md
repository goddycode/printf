# printf

### Description

------------


The printf function sends formatted output to stdout.
A custom _printf() for learning purposes was developed by Goddy Odhis and Weke Victor.
_printf() function format string is a character string, beginning and ending in its initial shift state, if any. 
These arguments are placed using the percentage '%' operator.

------------


#### Resources

------------


Secrets of printf by Thomas Samuel
https://www.academia.edu/10297206/Secrets_of_printf_

------------



#### Authorized functions and macros

------------


- write (man 2 write)
- malloc (man 3 malloc)
- free (man 3 free)
- va_start (man 3 va_start)
- va_end (man 3 va_end)
- va_copy (man 3 va_copy)
- va_arg (man 3 va_arg)

------------

#### Compilation

------------



The code is to be compiled this way:

**$ gcc -Wall -Werror -Wextra -pedantic *.c**

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)

The main files will include your main header file (main.h): **#include main.h**

------------

#### Use & Examples


------------

**Prototype:** int _printf(const char *format, ...);
**Use - General:** _printf("format string", var1, var2, ...);

**Examples:**
 - Basic String: _printf("%s ALX", "Hello");`
	 - Output: Hello ALX

- Print integers: _printf("This is an array element: arr[%d]:%c", 32, arr[32]);`
	- Output: This is an array element arr[32]:A
