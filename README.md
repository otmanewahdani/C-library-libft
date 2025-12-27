# Libft

A static C library inspired by 42 school projects.  This library involves re-writing a set of c standard library functions and also creating some new other useful functions. This library is a stepping-stone to completing most projects in the 42 curriculum, since only a handful of external functions are allowed (listed below).

## Highlights

**Ft_printf:** My own printf implementation. supported Conversions: c, s, d, i, u, x, X, p.
supported Flags: '#', '0', space, '+', '-', ' . ' .

**Get_next_line:** A file I/O function that allows to read a file descriptor a line at a time without losing the reading thread.

## External syscalls/functions
* <font size="5em"> Write </font>
* <font size="5em"> Read </font>
* <font size="5em"> Malloc </font>
* <font size="5em"> Free </font>

## Usage
To create libft.a, in the base directory of the repository run:
```
make
```
To delete the temporary object files, run:
```
make clean
```
To link libft to your program, make sure you include <libft.h> in your program files and specify the directory containing libft.h, i.e: incs/. Use the following flags with your C compiler:
```
<your-compiler> <your-program-files> -I/path/to/incs -L/path/to/libft.a -lft
```
