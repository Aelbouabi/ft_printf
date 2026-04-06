# 🖨️ ft_printf

> *Because `putnbr` and `putstr` aren't enough. My own implementation of the famous `printf` function, built at 1337 Coding School.*

## 💡 About The Project

`ft_printf` is a project that mimics the behavior of the standard C library `printf` function. The primary goal of this project is to learn how to use **variadic arguments** in C (via `stdarg.h`) to handle an unknown number of parameters of varying types. 

Rebuilding this function provided a deep dive into string formatting, memory management, and code structure, as the standard `printf` is surprisingly complex under the hood. Like `libft`, this function becomes a crucial tool for all subsequent C projects in the curriculum.

> **Note on Timeline:** This project was completed approximately two years ago during the earlier stages of the curriculum. I am archiving it here on this new GitHub account to document my progression as a developer.

## ⚙️ Supported Conversions

This implementation handles the following format specifiers:

* **`%c`** : Prints a single character.
* **`%s`** : Prints a string (as defined by the common C convention).
* **`%p`** : The `void *` pointer argument has to be printed in hexadecimal format.
* **`%d`** : Prints a decimal (base 10) number.
* **`%i`** : Prints an integer in base 10.
* **`%u`** : Prints an unsigned decimal (base 10) number.
* **`%x`** : Prints a number in hexadecimal (base 16) lowercase format.
* **`%X`** : Prints a number in hexadecimal (base 16) uppercase format.
* **`%%`** : Prints a percent sign.

## 🚀 Getting Started

### Prerequisites
* A C compiler (e.g., `gcc` or `clang`)
* `make`

