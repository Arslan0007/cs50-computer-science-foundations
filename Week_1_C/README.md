# Week 1: C and the "Truth" of Memory

## 🎯 Objective
Transitioning from Scratch (visual blocks) to C (text-based programming). The goal is to understand what happens "under the hood" of modern software: memory management, compilation, and the limitations of binary representation.

## 🧠 Key Concepts Learned

### 1. The Cost of Abstraction
In Python or JavaScript, we take numbers for granted. In C, we learn that **Data Types Matter**:
* `int` (4 bytes): Can run out of space (Integer Overflow).
* `float` (4 bytes): Can lose precision (Floating Point Imprecision).
* **Lesson:** Hardware has physical limits. Software bugs often come from ignoring these limits.

### 2. Compilation Process
Understanding that code doesn't just "run." It goes through a pipeline:
`Preprocessing` -> `Compiling` -> `Assembling` -> `Linking` -> `Binary Executable`

### 3. Memory & Truth
Computer memory is finite. Learning C teaches us that we must manage resources manually. This is the foundation for understanding "Memory Leaks" and "Buffer Overflows" in production systems.

## 🛠 Projects (Coming Soon)
* **Mario:** Building a pyramid using nested loops (Logic).
* **Cash/Credit:** implementing greedy algorithms (Efficiency).