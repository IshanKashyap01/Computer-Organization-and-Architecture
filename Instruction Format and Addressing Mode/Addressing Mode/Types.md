# Types of Addressing Modes

## Immediate

- The address field of the instruction stores the actual operand itself

- It is used to handle constants and intermediate data within instructions

- Therefore, the size of the operand depends on the bits allocated to the address
field

## Memory Direct / Absolute

The address field holds the physical address of the operand

## Memory Indirect

The address field stores the address where the effective address of the operand
is stored

## Register Direct

The address field holds the name of the register that contains the operand

## Register Indirect

The address field holds the name of the register that holds the effective address
of the operand

## PC-Relative

The address field stores a signed offset value that is added to the program counter
to find the address of the operand

## Base Register

The address field stores an offset value that is added the value stored in a GPR
(known as base register) to find the address of the operand

## Index Register

The values of two GPRs known as base and index register are added along with an
optional offset value in the instruction to find the operand's address

## Auto Decrement (Pre-decrement)

- The value of the SP register is decremented by a fixed number before accessing
the memory location

- It is generally used for the `POP` operation

## Auto Increment (Post-increment)

- The value of the SP register is incremented by a fixed number after accessing
the memory location

- It is generally used for the operations like `LDR` (load)

## Implied/Implicit

The operand is implicitly specified by the opcode itself
