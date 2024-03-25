# Instruction Cycle

- It is also known as the *fetch-decode-execute* cycle

- It is the basic operation performed by a CPU to execute an instruction

- A new instruction is not started until the current instruction has finished its
execution

## Fetch Cycle

- The `CU` copies the address location pointed by the `PC` into the `MAR`

- The `MMU` translates it to physical address and stores it back into the `MAR`

- The `CU` commands the system bus to retrieve the instruction stored at this
location

- The `CU` stores the result in `MBR`, then transfers it to the `IR`

- The `PC` is incremented to the start of the next instruction

## Decode Cycle

- The CPU interprets the instructions and determines the operation to be performed

- It identifies the `opcode` and its `operands` needed for the execution of the
instruction

- `Opcode` is the first byte of an instruction in machine language that represents
an operation in either binary or hexadecimal

### Fetch Operands

In some CPUs, the operands needed for an operations are fetched during a separate
cycle known as the `fetch operands cycle`

## Execute Cycle

- The CPU performs the operation decoded from the `decode` phase

- It may involve read/write, arithmetic/logical and/or program flow decision-making
operations

- Therefore, all major components of the CPU (`MMU`, `ALU` & `CU`) may be involved

### Store Results

In some CPUs, the results of an instructions are stored during a separate cycle
known as the `store results cycle`

## Interrupt Handling

- The CPU may receive an interrupt signal which will suspend the current instruction

- The CPU will execute an *interrupt handler* service to handle the interruption

- The value of the `PC` will be pushed onto the stack and transfer control to
interrupt program
