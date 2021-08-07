## MMU
- The memory management unit is a hardware component that is responsible for the memory management operations by the processor

- The
MMU divides the virtual address space into pages, which it accesses to retrieve
information from memory

- The
pages are mapped to memory by replacement algorithms

____

**In** this project replacement algorithms were implemented:
LRU, MFU, RANDOM

**This**
system simulates the operation of a memory management unit (MMU)
by caching the relevant pages (according to the selected replacement algorithm).
Cache full, Page Fault will be replaced, again by the algorithm we chose earlier.

**This** system used
a number of programming principles, such as:

◦
Strategy Pattern

◦
Observer pattern