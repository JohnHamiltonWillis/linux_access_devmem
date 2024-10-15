# Overview
This repository provides a C++ API for interacting with the /dev/mem driver, enabling direct memory access on Linux systems. It includes functions to read from and write to physical memory locations, as well as utility functions for working with memory regions as vectors or files.

# Features
* Memory Access: Functions to read and write 32-bit values directly from/to physical memory.
* Vector Support: Read from and write to memory using vectors for bulk operations.
* File I/O: Read memory contents to a file and write from a file to memory.

# Requirements
* Linux-based system with access to /dev/mem.
* C++ compiler that supports C++11 or later.

# Usage
This API is intended for low-level system programmers or developers working on embedded systems that require direct memory access.
