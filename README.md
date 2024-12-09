# Multi-Threading and Multi-Processing in Python

This repository demonstrates concepts and examples of **multi-threading** and **multi-processing** in Python. It explores the fundamental differences, advantages, and limitations of using threads and processes for concurrent and parallel programming.

## Contents

### 1. Multi-Threading
- **Concept**: Threads are lightweight processes that share memory. They allow tasks to run concurrently in the same process.
- **Topics Covered**:
  - Thread creation using the `threading` module.
  - Synchronization using `Lock`, `RLock`, `Semaphore` and `Barrier object`.
  - Thread-safe operations using GIL.
  - Demonstrations of race conditions and Solutions.

### 2. Multi-Processing
- **Concept**: Processes are independent execution units with their own memory space. They enable true parallelism on multi-core CPUs.
- **Topics Covered**:
  - Process creation using the `multiprocessing` module.
  - Shared memory with `Value` and `Array`.
  - Using `Manager` for shared data structures like lists and dictionaries.
  - Synchronization using `Lock`, `RLock`, and `Queue`.
  - Demonstrations of process communication using `Pipe` and `Queue`.
  
## Why Learn This?
- **Multi-threading**: Useful for I/O-bound tasks like file handling, web scraping, and database operations.
- **Multi-processing**: Ideal for CPU-bound tasks like numerical computations, image processing, and simulations.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Susan246/Multi-Threading-and-Multi-Processing-in-Python.git
   cd Multi-Threading-and-Multi-Processing-in-Python
