# Machine Instruction

- Machine instructions are directly executed by a CPU

- Each machine instruction is a very specific, single operation such load, jump,
or an ALU operation

## Machine Instructions Used in 8086 Microprocessor

Note: the instructions are performed on a byte or a word

### Data Transfer Instructions

- `MOV`: move to register/memory

- `IN`, `OUT`: I/O to or from port

- `LEA`: load effective address

- `LDS`, `LES`: load pointer using data segment or extra segment

- `PUSH`, `POP`: push or pop on/off the stack

- `XCHG`: exchange

- `XLAT`: translate byte using lookup table

### Arithmetic Instructions

- `ADD`, `SUB`: add, subtract

- `ADC`, `SBB`: add, subtract byte/word and carry, borrow

- `INC`, `DEC`: increment, decrement

- `NEG`: negate (two's complement)

- `CMP`: compare (subtract w/o storing)

- `MUL`, `DIV`: multiply, divide (unsigned)

- `IMUL`, `IDIV`: multiply, divide (signed)

- `CBW`, `CWD`: convert byte to word, word to double word

- `AAA`, `AAS`, `AAM`, `AAD`: ASCII adjust for add, sub, mul, div

- `DAA`, `DAS`: decimal adjust for add, sub (BCD numbers)

### Logical Instructions

Apart from `AND`, `OR`, `XOR`, and `NOT`, there are following logical instructions:

- `TEST`: test w/o storing

- `SHL`, `SHR`: logical shift rotate instruction left, right

- `SAL`, `SAR`: arithmetic left, right shift

- `ROL`, `ROR`: rotate left, right

- `RCL`, `RCR`: rotate left, right through carry byte or word
