# ERPLAG-Compiler
# Multi-Pass Compiler Project

A complete **multi-pass compiler** implemented from scratch in **C**, designed to translate a custom high-level language into **NASM assembly**. This project implements the full compilation pipeline, including:

- **Lexical Analysis** – tokenizing source code  
- **Recursive Descent Parsing** – building parse trees from the grammar  
- **Semantic Analysis** – performing type checks and ensuring code correctness  
- **Code Generation** – producing NASM assembly code from the abstract syntax tree  

This project demonstrates a hands-on understanding of compiler design principles and low-level code generation.

---

## Group Information

**BITS Pilani – Group 43**

| Name | ID |
|------|----|
| Rahul B | 2019A7PS0134P |
| Asish Juttu | 2019A7PS0039P |
| Narasimha Gupta Jangala | 2019A7PS0138P |
| Praneeth Chaitanya Jonnavithula | 2019A7PS1111P |
| Damargidda Rohan Raj Goud | 2019A7PS0065P |

---

## Getting Started

### Prerequisites
- GCC Compiler  
- NASM assembler  

### Compilation
```bash
gcc -o compiler main.c lexer.c parser.c semantic.c codegen.c
