# Tiny Ruby Compiler in C

A toy Ruby-like compiler and virtual machine written entirely in **C**.  
This project demonstrates how a high-level scripting language can be parsed, compiled, and executed step by step.  

## ✨ Features
- **Lexer & Parser** – Tokenizes source code and parses it using a Pratt-style parser.  
- **AST (Abstract Syntax Tree)** – Source is transformed into an intermediate tree form.  
- **Bytecode Compiler** – Compiles AST into a custom stack-based bytecode.  
- **Virtual Machine (VM)** – Executes bytecode instructions (`PUSH_INT`, `ADD`, `SUB`, `MUL`, `DIV`, `PRINT`, `CALL`, etc.).  
- **Functions & Return** – Supports top-level `def` functions and `return`.  
- **Garbage Collector** – Minimal **mark-and-sweep** GC for heap objects (strings and functions).  
- **REPL & Script Execution** – Interactive shell or `.rb` script execution.  

## 🚀 Getting Started

### Build
```bash
gcc -O2 -o tiny_ruby tiny_ruby_c_single_file.c
