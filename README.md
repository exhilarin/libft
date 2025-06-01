# 🧱 Libft

![42 Project](https://img.shields.io/badge/42%20Network-Libft-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-C-blue?style=for-the-badge)

## 📚 Project Summary

**Libft** is the very first project in the 42 curriculum. Its goal is to create a custom C library by re-implementing standard C functions from scratch, without relying on the standard library itself.  
This project builds a solid foundation in C programming by teaching manual memory management, string and character manipulation, data structures, and modular code design.  
Libft lays the groundwork for future projects like `get_next_line`, `ft_printf`, and more complex system-level tasks.

---

## 🧠 What I Learned in Libft

The **Libft** project teaches a wide range of essential programming concepts and skills that form the foundation of C development:

### 🔹 Low-Level Memory Management
- Manual allocation with `malloc`, deallocation with `free`.
- Writing functions like `memset`, `memcpy`, `memmove`, and `memcmp`.
- Deepened understanding of memory operations and safety.

### 🔹 String and Character Manipulation
- Implementing string-related functions like `strlen`, `strlcpy`, `strchr`, `strrchr`, `strncmp`, and `strnstr`.
- Handling null-terminated strings without built-in functions.
- Learning how character arrays work in low-level memory.

### 🔹 ASCII Character Handling
- Creating functions like `isalpha`, `isdigit`, `isalnum`, `isascii`, `isprint`, `toupper`, and `tolower`.
- Working with ASCII values and character validation logic.

### 🔹 Function Design & Modularity
- Creating clean, reusable C functions.
- Using header files (`libft.h`) to manage function prototypes.
- Following a consistent and maintainable code style.

### 🔹 Dynamic Memory & Data Structures
- Functions like `calloc`, `strdup`, and dynamic string manipulation.
- Bonus part: implementing a **singly linked list** with:
  - `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`
  - `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`
- Gained practical experience with pointers and recursive data structures.

### 🔹 Makefile Usage
- Writing a custom `Makefile` for compiling the library.
- Understanding targets like `all`, `clean`, `fclean`, and `re`.

### 🔹 Norminette & Code Standards
- Writing code that strictly follows 42’s **Norminette** coding style.
- Improved discipline in formatting, naming, and file organization.

---

## 📁 Project Structure

```bash
libft/
├── ft_*.c              # Custom implementations of standard functions
├── ft_lst*.c           # Linked list bonus functions
├── libft.h             # Header file containing function prototypes
├── Makefile            # Build automation
└── README.md           # Project documentation
