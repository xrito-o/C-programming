---
title: Home
layout: home
nav_order: 1
---

# **C Programming**

## **What is C?**s

C is a general-purpose programming language created by **Dennis Ritchie** in 1972 at Bell Labs. It is fast, powerful, and forms the foundation of many modern languages. C is closely tied to the development of **UNIX**.

---

## **[Constants](/C-programming/docs/constants-in-c.html)**

Constants are fixed values that **do not change** during program execution.
They can be **Primary** (integer, floating-point, character) or **Secondary** (string, array, pointer, enum, struct, macro).

---

## **[Variables](/C-programming/docs/variables-format-specifiers-in-c.html)**

Variables are named memory locations used to store data.
They can hold constants such as integers, characters, or floating-point numbers.
Example:

```c
int age = 25;
```

---

## **[Data Types](/C-programming/docs/data-types-of-c.html)**

Data types define the **type** and **size** of data a variable can store.
Examples: `int` (4 bytes), `float` (4 bytes), `double` (8 bytes), `char` (1 byte), `void` (no value).

---

## **[Operators](/C-programming/docs/operators-in-c.html)**

Operators are symbols that perform operations on variables and values.
Main categories include:

* Arithmetic
* Assignment
* Comparison
* Logical

---

## **[Header File Libraries](/C-programming/docs/header-file-libraries-in-c.html)**

Header files contain **function declarations**, **macros**, and **definitions**.
They allow you to use built-in functions like `printf()` without writing them yourself.
Example: `<stdio.h>` for input/output functions.

---

## **Hello World Program**

```c
#include <stdio.h>

int main() {
    printf("Hello World!");
    return 0;
}
```
fafawfa