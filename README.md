# Completed with CS 61 Class - Synchronization with self-coded reading and writing library(stdio style)

Implemented synchronization on self-coded reading and writing library which outperforms stdio. 
Uses locking(fine-grained vs coarse-grained) to allow safe multithreading. 
Uses caches, seeking, and flushing to outperform sequential and non-sequential read write accesses compared to stdio.

Extra Credit phase 4, integrating Pset 4 IO61 library with Pset 6
Functions: write,writec,read,readc,close, and open functions.
