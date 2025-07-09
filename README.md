# Custom-Memory-Allocator
This repository contains a simple, educational block-based memory allocator implemented in C. The allocator manages a fixed-size memory space, dividing it into blocks with headers to track allocation status and block size. It supports basic dynamic memory allocation and operations, as well as a function to display the current memory layout.

# Key Features
**Block-Based Allocation:** Manages memory in blocks with headers, tracking size and allocation status.

**Manual Memory Management:** Provides alloc and destroy functions for dynamic memory allocation and deallocation.

**Fragmentation Handling:** Splits free blocks when possible to minimize wasted space.

**Allocation Visualization:** Includes a utility to display the current allocation status of memory blocks.

**Educational Design:** Simple, readable code ideal for learning about memory management internals.

**Example Usage**

int8 *p = (int8*)alloc(7);.
int8 *p2 = (int8*)alloc(2000);.
destroy(p2);.
show_allocation();.
