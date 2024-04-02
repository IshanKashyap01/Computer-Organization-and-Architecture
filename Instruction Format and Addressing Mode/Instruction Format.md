# Instruction Format

- An instruction contains an opcode followed by either the operands or their
address fields

- With `n` bits for opcode, we can represent $2^n$ operators in an instruction

- The address field can be either register or memory address field

## Types of Instruction Format

### Fixed-Length

- Each instruction has fixed size, with specific bits allocated for opcode,
operands and other fields

- It simplifies decoding and execution but limits the range of operations and
addressing modes that can be supported

### Variable-Length

- Size of each instruction can vary allowing more flexibility in encoding complex
operations and addressing modes

- It typically includes a length field or delimiter to indicate the end of the
instruction

### Three-Address

- Specifies three operands: two source and one destination

- Commonly used for arithmetic operations to store the value of an operation in
the same instruction

### Two-Address

- Specifies two operands: a source and a destination

- Commonly used for moving or copying operations

### One-Address

Containing only one operand, it's commonly used for accessing data from memory

### Zero-Address

- The operands are implied by the opcode itself or by the current state of the
CPU and memory

- Often used for stack-based or register-based operations

### Register Address

- The instruction specifies one or more operands as register addresses

- It is efficient when operands are stored in registers
