# Ft_printf

This is the ft_printf function, which is an implementation of the printf function, done as a school project at 42.

## Description

This function is a duplicate of the printf function, which is used to output formatted data. It accepts format specifiers and arguments, which are replaced by their corresponding values in the output string.

The following format specifiers have been implemented in this version of ft_printf:

- %d or %i: for printing signed decimal integers.
- %c: for printing a single character.
- %s: for printing a string.
- %u: for printing unsigned decimal integers.
- %x or %X: for printing hexadecimal integers in lowercase or uppercase, respectively.
- %p: for printing a pointer address.

## Usage

To use 'ft_printf', simply include the 'ft_printf.h' header file and call the 'ft_printf' function with the desired format string and any necessary arguments:

```c
#include "ft_printf.h"

int main()
{
    ft_printf("Hello, %s!\n", "world");
    ft_printf("The answer is %d.\n", 42);
    return 0;
}
```

It accepts a format string as its first argument, followed by any number of optional arguments. The format string may contain format specifiers, which begin with a % character, and are followed by a conversion specifier.

Here is an example of how to use ft_printf:

```c
  ft_printf("Hello, %s!\n", "world");
```

## Return Value

The 'ft_printf' function returns the number of characters printed, or a negative value if an error occurred.

## Limitations

This implementation of 'ft_printf' has the following limitation:

It does not support all of the format specifiers that are supported by the printf function in the standard library.

## Building and testing

To build and test ft_printf, clone this repository and run make:

```shell

git clone https://github.com/alpardayalman/ft_printf_origin.git
cd ft_printf
make
```

## Contributing

If you find a bug or would like to contribute to 'ft_printf', feel free to open an issue or pull request on GitHub.
