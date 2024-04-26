# Types of Registers

## Program Counter (PC)

- Contains the starting address (virtual) of the next instruction to be executed

## Instruction Register (IR)

- Holds the current instruction being executed

- The instruction format is predefined in the IR

## (Memory) Address Register (MAR/AR)

- Stores the address of the memory location currently accessed or referenced

- It holds the address until the read/write operation is finished

- Used by MMU to fetch and store data

- Connected to the `address line` of the system bus

## Memory Buffer Register (MBR)

- Temporarily holds data during data transfer b/w CPU and h/w

- Connected to the `data line` of the system bus

## Data Register (DR)

- Temporarily store data during processing and data transfer within the CPU

- Connected to the `data line` of the system bus

## Accumulator Register (AC)

- Serves as a temp storage by ALU for storing intermediate results during
calculations

- It can also be used for making decisions about branching in program flow

## Stack Pointer Register (SP)

- Tracks the top of the stack in the memory in a stack based memory organization

- Heavily used during function calls and returns

- Often used during interrupt handling to save the current state of the CPU onto
the stack before jumping to interrupt service routine

## Program Status Word Register (PSW)

- Contains various flags and control bits to represent the state of the CPU as well
as the outcome of recent ALU operations

- `Control bits` control various aspects of CPU ops such as interrupt flags, mode
bits (user/superuser), etc.

- `Execution mode`: current mode of execution such as kernel or user mode

### Status Flags

- `Z` (*Zero Flag*): whether the result of the previous operation was zero

- `S` (*Sign Flag*): the sign of the previous result (positive or negative)

- `C` (*Carry Flag*): carry/borrow during arithmetic operations

- `V` (*Overflow Flag*): whether the result overflowed its range

- `P` (*Parity Flag*): the parity (even or odd) of the result

## General Purpose Register (GPR)

Not designed for a specific use, they can perform various operations in a flexible
manner

- They can be used for ALU operations, data storage & manipulation, address calculation,
register renaming, function arguments and return values
