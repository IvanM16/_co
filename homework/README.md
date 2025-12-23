# 🧠 NAND2TETRIS Project Explanation (Projects 1–12)

ALL COPIED FROM [dy546](https://github.com/dy546/_co/tree/main/homework) WITH SOME MODIFY

The NAND2TETRIS course teaches you how to build a complete computer system from first principles, starting with a single logic gate (NAND) and ending with a working computer capable of running games like Tetris.

🔹 Project 1 – Boolean Logic
Goal

Build basic logic gates using only the NAND gate.

Components Built

- NOT

- AND

- OR

- XOR

-   Multiplexor (MUX)

- Demultiplexor (DMUX)

Key Concept

The NAND gate is functionally complete, meaning any logic circuit can be built from it.

What You Learn

- Boolean algebra

- Hardware Description Language (HDL)

- How simple logic forms the foundation of all computers

🔹 Project 2 – Boolean Arithmetic
Goal

Build arithmetic circuits for binary computation.

Components Built

- Half Adder

- Full Adder

- Add16 (16-bit adder)

- Incrementer

- Arithmetic Logic Unit (ALU)

Key Concept

Computers perform calculations using binary arithmetic.

What You Learn

- Binary addition

- Overflow handling

- ALU control logic (zero flag, negative flag)

🔹 Project 3 – Sequential Logic
Goal

Introduce memory into the computer.

Components Built

- Bit

- Register

- RAM8, RAM64, RAM512, RAM4K, RAM16K

- Program Counter (PC)

Key Concept

Memory enables computers to remember past states.

What You Learn

- Clocked circuits

- Registers and RAM hierarchy

- Addressing memory locations

🔹 Project 4 – Machine Language
Goal

Learn the low-level language understood by the computer.

Tasks

Write programs in Hack Assembly

Examples:

- Multiply numbers

- Fill the screen

- Keyboard interaction

Key Concept

Machine language controls the hardware directly.

What You Learn

- Assembly instructions

- Registers (A, D)

- Memory-mapped I/O

🔹 Project 5 – Computer Architecture
Goal

Build the Hack Computer.

Components Connected

- CPU

- Instruction Memory (ROM)

- Data Memory (RAM)

- Input (Keyboard)

- Output (Screen)

Key Concept

A computer is a coordinated system of hardware modules.

What You Learn

- Fetch–Decode–Execute cycle

- Instruction execution flow

- Hardware-software interaction

🔹 Project 6 – Assembler
Goal

Create a program that translates Hack Assembly to binary machine code.

Input


```
asm

@2
D=A
@3
D=D+A
```

Output
```
text

0000000000000010
1110110000010000
```
Key Concept

Assemblers bridge human-readable code and machine code.

What You Learn

- Symbol tables

- Binary encoding

- Parsing text files

🔹 Project 7 – VM Translator (Part 1)
Goal

Translate Virtual Machine (VM) commands into Hack Assembly.

Commands Covered

- Arithmetic operations (add, sub, neg)

- Logical operations (eq, gt, lt)

- Memory access (push, pop)

Key Concept

VM code is a portable abstraction over hardware.

What You Learn

- Stack-based computation

- Memory segments (local, argument, static, constant)

🔹 Project 8 – VM Translator (Part 2)
Goal

Extend the VM Translator to support program control and function calls.

Commands Added

- label, goto, if-goto

- function, call, return

Key Concept

Function calls require stack frames and return addresses.

What You Learn

- Call stack management

- Recursion

- Program flow control

🔹 Project 9 – High-Level Programming
Goal

Write programs in Jack, a high-level language.

Examples

- Calculator

- Simple games

- Data structures

- Key Concept

High-level languages improve productivity and readability.

What You Learn

- Classes and methods

- Control structures

- Object-oriented concepts

🔹 Project 10 – Compiler (Syntax Analysis)
Goal

Build the front end of the Jack compiler.

Output

XML representation of the program structure

Key Concept

Compilers must understand grammar and syntax.

What You Learn

- Tokenizing source code

- Parsing expressions

- Abstract Syntax Trees (AST)

🔹 Project 11 – Compiler (Code Generation)
Goal

Complete the compiler by translating Jack code into VM code.

Key Concept

High-level constructs map to low-level instructions.

What You Learn

- Symbol tables

- Scope handling

- Memory allocation

- Expression evaluation

🔹 Project 12 – Operating System
Goal

Implement a basic operating system in Jack.

OS Modules

- Memory management

- Math library

- String handling

- I/O services

- Keyboard & Screen control

Key Concept

An OS provides essential services to applications.

What You Learn

- System-level abstraction

- Resource management

- Full software stack integration

🏁 Final Result

By the end of Project 12, you have built:

✅ Logic gates

✅ Arithmetic circuits

✅ Memory

✅ CPU

✅ Computer

✅ Assembler

✅ Virtual Machine

✅ Compiler

✅ Operating System

➡️ A complete computer system from NAND gates to running Tetris