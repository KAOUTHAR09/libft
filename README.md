# <div align="center">Libft</div>

## Preview
Welcome to my **libft** project repository! This project is part of the 42 cursus and involves creating a personal C library. The goal of libft is to understand the basics of memory management and the C programming language while implementing various standard library functions.

## 🌟 About libft
**libft** is a foundational project in the 42 curriculum that requires students to recreate several standard library functions and to implement additional functionalities. This project is crucial for building a strong understanding of C programming concepts, memory allocation, and data manipulation.

### 📚 Objectives
- Implement standard C library functions that are commonly used, including but not limited to:
  - `malloc`
  - `free`
  - `strdup`
  - `memset`
  - `memcpy`
  - `strlen`
  - `strchr`
  - `strrchr`
  - `strcmp`
  - `strncmp`
  - `strncat`
  - `strlcpy`
  - `strlcat`

- Create additional utility functions that enhance the functionality of the library, such as:
  - `ft_atoi`
  - `ft_striteri`
  - `ft_lstnew`
  - `ft_lstadd_front`
  - `ft_lstsize`
  - `ft_lstlast`
  - `ft_lstadd_back`
  - `ft_lstdelone`
  - `ft_lstclear`
  - `ft_lstiter`
  - `ft_lstmap`

### 🔧 Functions Overview

Here’s a brief overview of some key functions included in **libft**:

#### Memory Management Functions:

- `void *ft_memset(void *b, int c, size_t len);`
- `void *ft_memcpy(void *dest, const void *src, size_t n);`
- `void *ft_calloc(size_t count, size_t size);`

#### String Manipulation Functions:

- `size_t ft_strlen(const char *s);`
- `char *ft_strdup(const char *s1);`
- `int ft_strcmp(const char *s1, const char *s2);`

#### Integer Functions:

- `int ft_atoi(const char *nptr);`

#### Linked List Functions:

- `t_list *ft_lstnew(void *content);`
- `void ft_lstadd_front(t_list **alst, t_list *new);`
- `int ft_lstsize(t_list *lst);`

## 🙌 Acknowledgments
A big thank you to the 42 community for their support and collaboration throughout this project. Special thanks to my peers for their invaluable feedback and assistance.
