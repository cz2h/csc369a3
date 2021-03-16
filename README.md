# csc369a3
csc369 a3, a simple virtual memory.
Implement the following features:
## Page table entry methods:
1. Page fault handler. When the present bit of PTE is 0, will go to the disk to swap in corresponding data.
2. Page fault handler, when there is no physical memory available, will use paging algorithm to swap page out.

## Paging algorithm
LRU, FIFO, OPT, rand
