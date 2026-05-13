# ft_printf

A custom implementation of the C `printf()` function that converts and prints formatted output to stdout.

## Features

- Supports multiple format specifiers:
  - `%d` / `%i` - Decimal integers
  - `%u` - Unsigned integers
  - `%x` - Hexadecimal lowercase
  - `%X` - Hexadecimal uppercase
  - `%s` - Strings
  - `%c` - Characters
  - `%p` - Pointers
  - `%%` - Percent sign

## Usage

You can use the provided `main` function in the `ft_printf.c` file

## Compilation

Build the static library:
```bash
make
```

Other targets:
- `make clean` - Remove object files
- `make fclean` - Remove object files and library
- `make re` - Rebuild from scratch

## Notes

- Returns the number of characters printed
- Returns `-1` if the format string is NULL
- Part of the 42 school curriculum

## Grade

100/100
