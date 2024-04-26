# Multiplexer (MUX)

- A multiplexer has multiple input lines that get converged into a single
output line

- The number of multiplexers required is equal to the size of the register it's
connected to (in bits)

- Whereas, the size of the MUX is equal to the number of registers

$$
N_{MUX} = S_{R_bits}
$$

$$
S_{MUX} = N_{R}
$$

*Where*:

- $N \rightarrow Number$

- $S \rightarrow Size$

- $R \rightarrow Register$

- For ex, if there are 8 registers, then each MUX will have 8 input connections

- Similarly, if the register size is 16 bits, then there will be 16 multiplexers

- The internal bus is connected to the multiplexers and each MUX is connected to a register
