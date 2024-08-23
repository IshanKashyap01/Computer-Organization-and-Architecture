# Design of CPU Instruction Pipeline

- The instruction execution lifecycle contains *fetch, decode, execute, memory*
*access* and *write back*

- These phases are divided into independent modules known as *stages, segments,*
or *pipes*

- Hence, each pipe can work on a different instruction in the same cycle

$$
ET_{pipeline} = [k + (n - 1)] \text{ cycles or } t_p
$$

- Here,

  - `ET` is the *execution time*,

  - `k` is the number of stages and

  - `n` is the number of instructions

  - $t_p$ is the cycle time in pipeline

- Therefore, average cycle time per instruction can be given as $[k + (n - 1)] t_p \over{n}$

- If we ignore $k - 1$, then **cycle per instruction (CPI) will be 1**

- Whereas, without pipelining, $ET = n * t_n$

  - Where, $t_n$ is the time taken by each instruction to execute without pipelining
