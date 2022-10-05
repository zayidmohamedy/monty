
![ ALX School of Software Engineering](https://lh3.googleusercontent.com/oVJxT1yn7vwaEM8t9A5MGL6emG0j-_uqHa5H8ikWLvl6Ka-nVmUJZblqWDqPiY-S6itPLnZNgcc8rviK8AVT65l_a3zHiyctwy8=s0)

## Description
In this project we are tasked to create an interpreter for Monty ByteCode files. These files will have commands per line to manipulate the data structure given.

What you should learn from this project:

* What do LIFO and FIFO mean.
* What is a stack, and when to use it.
* What is a queue, and when to use it.
* What are the common implementations of stacks and queues.
* What are the most common use cases of stacks and queues.
* What is the proper way to use global variables.
* How to work with git submodules.

---
## Requirements

## Files

### [monty.c](./monty.c)
* Contains the main function that takes in the file and runs the parser.

### [monty.h](./monty.h)
* Header file.

### [parse.c](./parse.c)
* Functions that parses the file from main, then parses the lines. While parsing, data is stored into structs to be passed onto other functions.

### [verify.c](./verify.c)
* Contains functions that checks arguments from lines of the file. Checks for if push function is in the file line.

### [match.c](./match.c)
* Our get operations function that matches the aruguments with what opcode function we need to run.

### [opcodes_1.c](./opcodes_1.c)
* Contains push, pall, free_stack, and nop.

### [opcodes_2.c](./opcodes_2.c)
* Contains pint, pop, swap, pchar, and pstr.

### [opcodes_3.c](./opcodes_3.c)
* Contains rotl, rotr, qpush.

### [opcodes_math.c](./opcodes_math.c)
* Contains add, sub, div, mul, mod.

### [opcodes_mode.c](./opcodes_mode.c)
* Contains stack and queue
---

## Tasks

### 0. push, pall
* Implement the push and pall opcodes.
* The opcode push pushes an element to the stack.
* The opcode pall prints all the values on the stack, starting from the top of the stack.

### 1. pint
* Implement the pint opcode.
* The opcode pint prints the value at the top of the stack, followed by a new line.

### 2. pop
* Implement the pop opcode.
* The opcode pop removes the top element of the stack.

### 3. swap
* Implement the swap opcode
* The opcode swap swaps the top two elements of the stack.

### 4. add
* Implement the add opcode.
* The opcode add adds the top two elements of the stack.

### 5. nop
* Implement the nop opcode.
* The opcode nop doesn’t do anything.

### Advanced Tasks
* opcodes: sub, div, mul, mod, comments, pchar, pstr, rotl, rotr, stack, queue.
---

## Authors

[zayid mohamed](https://github.com/zayidmohamedy)

 

