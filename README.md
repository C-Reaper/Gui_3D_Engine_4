# Project README

## Overview
This project is a simple C library for 3D mathematics, including basic vector operations, matrix transformations, and geometric calculations. The library provides a header file (`math3d.h`) that can be included in your C programs to perform 3D math operations.

## Features
- Vector operations (addition, subtraction, scalar multiplication, dot product, cross product)
- Matrix operations (transformation, inversion, determinant calculation)
- Geometric calculations (intersection of lines and planes)

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Standard development tools

## Build & Run
To build the library and example program, follow these steps:

1. **Build the Library:**
   ```sh
   cd <Project>
   make -f Makefile.linux lib  # For Linux
   make -f Makefile.windows lib  # For Windows
   make -f Makefile.wine lib  # For Linux cross compile for windows
   ```

2. **Build and Run the Example Program:**
   ```sh
   make -f Makefile.linux do  # For Linux
   make -f Makefile.windows do  # For Windows
   make -f Makefile.wine do  # For Linux cross compile for windows
   ```
   
3. **Execute the Example Program:**
   ```sh
   ./build/Main  # For Linux
   Main.exe  # For Windows
   ```

The project includes a simple example program (`Main.c`) that demonstrates how to use the 3D math library functions. The `Makefile` is provided for building on different platforms (Linux, Windows).

### Directory Structure
```
<Project>/
├── build/              # .exe files produced by Main.c
├── src/                # source code
│   ├── Main.c          # Entry point
│   └── math3d.h        # header file for 3D math operations
└── Makefile.linux      # Linux Build configuration
└── README.md           # This file
```

### Notes:
- The project does not require any external libraries beyond the standard C library.
- The build process is simplified to demonstrate basic makefile usage.