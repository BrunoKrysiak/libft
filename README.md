# Libft

**Status:** Completed ✅

Custom implementation of standard C library functions as part of the 42 Warsaw curriculum.

---

## 📚 Project Overview

Libft is a foundational project focused on recreating essential functions from the standard C library.  
The goal is to build a deep understanding of low-level programming, memory management, and core C concepts by implementing these functions from scratch.

This project serves as the base for many future projects at 42, where a solid understanding of these utilities is required.

---

## 🎯 Objectives

- Reimplement standard C library functions  
- Understand memory allocation and manipulation  
- Practice writing clean, reusable and efficient code  
- Build a personal library for future projects  

---

## 🧠 Skills Developed

- Low-level programming in C  
- Memory management (malloc, free, pointers)  
- String and buffer manipulation  
- Algorithmic thinking  
- Code organization and modular design  

---

## ⚙️ Technical Details

- Language: C  
- Standard: 42 Norm (norminette compliant)  
- Output: Static library (`libft.a`)  
- Compilation: via `Makefile`  

---

## 🔧 Usage

Clone the repository:

```bash
git clone https://github.com/BrunoKrysiak/libft.git
cd libft
```

Compile the library:

```bash
make
```

This will generate the static library:

```bash
libft.a
```

---

## 📦 Implemented Functions

### 🔹 Libc functions
- ft_strlen  
- ft_strdup  
- ft_strcpy / ft_strncpy  
- ft_strncmp  
- ft_strchr  
- ft_strrchr  
- ft_strnstr  
- ft_strlcpy  
- ft_strlcat  

### 🔹 Memory functions
- ft_memset  
- ft_bzero  
- ft_memcpy  
- ft_memmove  
- ft_memchr  
- ft_memcmp  
- ft_calloc  

### 🔹 String manipulation
- ft_substr  
- ft_strjoin  
- ft_strtrim  
- ft_split  

### 🔹 Character checks
- ft_isalpha  
- ft_isdigit  
- ft_isalnum  
- ft_isascii  
- ft_isprint  

### 🔹 Conversion
- ft_atoi  

### 🔹 Output functions
- ft_putchar_fd  
- ft_putstr_fd  
- ft_putendl_fd  
- ft_putnbr_fd  

---

## 📁 Project Structure

```
libft/
│
├── ft_*.c
├── libft.h
├── Makefile
└── README.md
```

---

## 🧪 Testing

All functions have been manually tested during development and evaluated according to 42 standards.

---

## 🧠 What I Learned

This project helped me understand how fundamental C functions work internally, especially memory handling and string manipulation.  
It built a strong foundation for more advanced projects like ft_printf and get_next_line.

---

## ⭐ Final Thoughts

Libft is more than just a collection of functions —  
it represents a deep dive into how fundamental operations in C really work under the hood.
