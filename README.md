```markdown
# libft - A Custom C Library

`libft.a` is a custom static library written in C. It provides a collection of commonly used functions to facilitate the development of various applications by mimicking functions from the standard C library, along with additional utilities.

## Getting Started

### Prerequisites
You need a C compiler to build this library. The Makefile uses the following flags for compilation:
- `-Wall`: enables all warnings about constructions.
- `-Wextra`: enables extra warnings.
- `-Werror`: treats all warnings as errors.

### Compiling the Library

To compile the library, simply run:
```bash
make
```

This will compile all the source files and create `libft.a`, a static library containing the implemented functions.

### Bonus Functions

The library also includes additional "bonus" functions for managing linked lists. To compile the library with these bonus functions, use:
```bash
make bonus
```

### Cleaning Up

- `make clean`: Removes all object files (`.o`) generated during compilation.
- `make fclean`: Removes all object files as well as the `libft.a` library.
- `make re`: Recompiles the library by running `fclean` and then `all`.

## Function List

### Core Functions

| Function      | Description                                      |
|---------------|--------------------------------------------------|
| `ft_atoi`     | Converts a string to an integer                  |
| `ft_atol`     | Converts a string to a long integer              |
| `ft_bzero`    | Sets a memory area to zero                       |
| `ft_calloc`   | Allocates memory and initializes it to zero      |
| `ft_isalnum`  | Checks if a character is alphanumeric            |
| `ft_isalpha`  | Checks if a character is alphabetic              |
| `ft_isascii`  | Checks if a character is ASCII                   |
| `ft_isdigit`  | Checks if a character is a digit                 |
| `ft_isprint`  | Checks if a character is printable               |
| `ft_itoa`     | Converts an integer to a string                  |
| `ft_memchr`   | Locates a byte in a block of memory              |
| `ft_memcmp`   | Compares two blocks of memory                    |
| `ft_memcpy`   | Copies memory area                               |
| `ft_memmove`  | Moves memory area                                |
| `ft_memset`   | Fills memory with a constant byte                |
| `ft_putchar_fd` | Writes a character to a file descriptor       |
| `ft_putendl_fd` | Writes a string with newline to a file descriptor |
| `ft_putnbr_fd`  | Writes a number to a file descriptor           |
| `ft_putstr_fd`  | Writes a string to a file descriptor           |
| `ft_realloc`    | Reallocates memory                             |
| `ft_split`      | Splits a string into an array of substrings    |
| `ft_strchr`     | Finds the first occurrence of a character in a string |
| `ft_strdup`     | Duplicates a string                            |
| `ft_striteri`   | Applies a function to each character of a string |
| `ft_strjoin`    | Concatenates two strings                       |
| `ft_strlcat`    | Appends a string to another, limited by size   |
| `ft_strlcpy`    | Copies a string with limited size              |
| `ft_strlen`     | Returns the length of a string                 |
| `ft_strmapi`    | Maps a function to each character of a string  |
| `ft_strncmp`    | Compares two strings up to a certain number of characters |
| `ft_strnstr`    | Finds a substring in a string                  |
| `ft_strrchr`    | Finds the last occurrence of a character in a string |
| `ft_strtrim`    | Trims whitespace characters from a string      |
| `ft_substr`     | Extracts a substring from a string             |
| `ft_tolower`    | Converts a character to lowercase              |
| `ft_toupper`    | Converts a character to uppercase              |

### Bonus Functions (Linked List Operations)

| Function          | Description                                  |
|-------------------|----------------------------------------------|
| `ft_lstadd_back`  | Adds an element at the end of a linked list  |
| `ft_lstadd_front` | Adds an element at the beginning of a linked list |
| `ft_lstclear`     | Clears and frees a linked list               |
| `ft_lstdelone`    | Deletes a single element from a linked list  |
| `ft_lstiter`      | Iterates a function over each list element   |
| `ft_lstlast`      | Returns the last element of a linked list    |
| `ft_lstmap`       | Creates a new list by applying a function to each element |
| `ft_lstnew`       | Creates a new list element                   |
| `ft_lstsize`      | Returns the size of a linked list            |

