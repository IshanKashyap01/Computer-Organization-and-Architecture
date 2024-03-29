# System Bus

- The system bus is a set of wires/traces that act as a means of communication
b/w the CPU and other devices

- It handles *transfer of data* in both directions i.e. to and from the CPU

- The *width* of a system bus determines how much data can be transmitted in
a single operation

- It also carries *control signals* that synchronize operations, signal the
beginning or end of data transfers and indicate read/write operations

## Components of System Bus

- `Address Bus`: carries addresses generated by the CPU to devices

- `Data Bus`: carries the actual data being transferred; consists multiple wires/
traces to form a parallel path

- `Control Bus`: carries the *control signals*

- `Bus Arbitration Logic`: manages access to bus and determines priority in systems
with multiple bus masters

- `Buffering & Signal Conditioning`: could be included in some cases; ensures
signal integrity
