# Expand Opcode Technique

- In fixed-length instruction format, the ISA is not natively scalable

- Therefore, to add more instructions than the bits allocated for the opcode
allows, we use this technique

- A shorter bit sequence is used as a prefix to indicate a set of opcodes
