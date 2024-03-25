# Byte & Word Addressable Memory Configurations

- Based on the cell size, memory configuration can be either *byte* or *word*
addressable

- In byte addressable configuration, the cell size is of one byte

- In word addressable configuration, the cell size is the same as the *word length*
*of the processor*

- The 64 bit and 32 bit architecture represents the word length

- The default memory configuration is byte addressable i.e. data is stored in
bytes

- However, CPUs are configured to read data in words

## Byte Ordering

- Suppose there is an instruction of 2 bytes: 0001 0000 0010 0000

- This instruction can be stored in the memory either as is or in reverse order
i.e. 0000 0100 0000 0001 (right to left)

- The former is known as the *big endian* whereas the latter is known as the
*little endian*

- The ordering of nibbles (4-bit) remains the same but their relative order is
changed

### Little Endian

- Little endian makes computing small numbers easier as the *least significant*
*bit* is placed first in the memory

- Little endian is the *industry standard* due to:

  - Efficiency in read/write operations over smaller units

  - To maintain *backwards compatibility* with the x86 architecture and its
  derivatives
