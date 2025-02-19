# Simplified Memory Management (SMM)

## Project Overview

The **Simplified Memory Management** project focuses on implementing a custom memory management system, which is a simplified version of the `malloc` and `free` functions, allowing users to manage memory directly without relying on the standard C library functions.

## Implementation Details

### Key Features

- **Custom Allocation Functions**: Implemented `mm_malloc()` to allocate memory and `mm_free()` to deallocate it, using a first-fit strategy for memory blocks.
- **Memory Layout Visualization**: After each operation, the program outputs the current memory layout, providing insights into the allocation and deallocation process.
- **Defragmentation**: Created a function to combine adjacent free memory blocks to reduce fragmentation over time.


