# :desktop_computer: 42Heilbronn :de:

<p align="center">
  <img src="https://github.com/Tilek12/42-project-badges/blob/main/badges/ft_printfe.png">
</p>

<h1 align="center">
 Project - ft_printf :printer:
</h1>

<h2 align="center">
 :white_check_mark: 100/100
</h2>

## :clipboard: Project info: [subject](https://github.com/Tilek12/42HN-ft_printf/blob/master/.git_docs_ft_printf/en.subject_ft_printf.pdf)

## :green_circle: **Mandatory Part**

Reproduction of a popular and versatile C function: printf(). 

**Program name**| libftprintf.a
:---|:---
**Turn in files**| Makefile, *.h, */*.h, *.c, */*.c
**Makefile**| NAME, all, clean, fclean, re
**External functs.**| malloc, free, write, va_start, va_arg, va_copy, va_end
**Libft authorized**| Yes
**Description**| Write a library that contains ft_printf(), a function that will mimic the original printf()


The prototype of ft_printf() is:
```
int ft_printf(const char *, ...);
```

### :eight_spoked_asterisk: **Requirements:**
- The buffer management of the original printf() is not implemented.
- Function handles the following conversions: cspdiuxX%
- Function compared against the original printf().
- The command ar is used to create your library.\
The libtool command is not used.
- libftprintf.a is created at the root of the repository

### :eight_spoked_asterisk: **Conversions:**
- **%c** Prints a single character.
- **%s** Prints a string (as defined by the common C convention).
- **%p** The void * pointer argument has to be printed in hexadecimal format.
- **%d** Prints a decimal (base 10) number.
- **%i** Prints an integer in base 10.
- **%u** Prints an unsigned decimal (base 10) number.
- **%x** Prints a number in hexadecimal (base 16) lowercase format.
- **%X** Prints a number in hexadecimal (base 16) uppercase format.
- **%%** Prints a percent sign.
