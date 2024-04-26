# Internal Bus

- The internal components of a CPU are also connected together with a Bus

- Therefore, only one signal is transmitted at a time inside the CPU

- This is because a point-to-point connection b/w every component within the
CPU would lead to too many wires and complexity

- For ex. if there are 8 registers, we only need 3 lines for the internal bus

- A signal flow from one register to another can be written as:
$R1_{out} \rightarrow R2_{in}$

- A component can be connected to the system bus for input, output or both

- The `MAR` and `MBR` are the only registers connected to the system bus

- The `MBR` has a two-way connection to the *data line* of the system bus as
well as to the internal bus

- $MAR_{in}$ is connected to the internal bus whereas $MAR_{out}$ is connected
to the *address line* of the system bus
