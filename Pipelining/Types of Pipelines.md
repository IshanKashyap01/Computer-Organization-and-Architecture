# Types of Pipelines

- During parallel processing, there is a *buffer delay* added between each stage
to store intermediate results

- The time taken by a stage to finish is called *stage delay*

- There is no buffer delay when pipelining is not used or only one instruction
is being executed

- Therefore, $t_n = \Sigma\text{stage delay}$

## Uniform Delay / Perfectly Balanced Pipeline

- Each stage takes the same amount of time to finish

- When a buffer delay is given, $t_p = \text{buffer delay + stage delay}$

- Therefore, if only one instruction is to be executed, $ET_{pipeline} = ET_{non-pipeline}$

- Moreover, $t_n = k \times{t_p}$

## Non Uniform Delay Pipeline

- Either each stage takes different time to finish *or* the delay between each
stage is different

- Therefore, $t_p = max(\text{stage delay + buffer delay})$ to let every stage
finish in one cycle

- This is so that the *cycle time* is *just long enough* for the *longest stage*
to finish

- Hence, maintaining an average CPI of 1

- However, if the *stage delay is shorter than* $t_p$, output is only released
after the end of the cycle
