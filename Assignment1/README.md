# Assignment1 - Circular Buffer Implementation (C)

## Project Description
This project implements a **Circular Buffer** in C language without using any built-in data structures.
The program supports:
- Buffer Initialization
- Writing (Enqueue)
- Reading (Dequeue)
- Handling Overflow and Underflow cases

## How it Works
1. The user enters their name using standard input.
2. The program appends the string **"CE-ESY"** to the name.
3. Each character is written into the circular buffer.
4. The program reads the data back from the buffer and prints it.
5. Finally, it checks that the buffer is empty.

## Features
- Circular buffer implemented using an array.
- Uses `head` for reading and `tail` for writing.
- Uses modulo operation to wrap around the buffer.
- Detects:
  - **Overflow** when buffer is full.
  - **Underflow** when buffer is empty.

## Files Included
- `prog.c` : Main source code.

## Notes
The buffer size was chosen smaller than the input string size to test the **Overflow** condition as required.

## How to Run
Compile and run using:

```bash
gcc prog.c -o prog
./prog
