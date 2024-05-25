# Micro Instructions

- The instruction cycle of a CPU has many minute operations

- These operations are called `micro instructions` or `micro operations`

- Each sub-cycle (fetch-decode-execution) involve one or more micro operations

- They are called "micro" because, they're very simple and accomplishes little

- For ex. moving data from one register from another

- Following is the microprogram for the `fetch cycle`:

    1. $T1: PC \rightarrow MAR$

    2. $T2: MAR \rightarrow MBR$ $PC + I \rightarrow PC$

    3. $T3: MBR \rightarrow PC$

## Micro Instruction Format

![*micro instruction format*](../images/micro%20instruction%20format.png)

- The `control field` contains the control signal in either *decoded* or *encoded*
format

| Category        | Horizontal           | Vertical         |
|-----------------|----------------------|------------------|
| Encoding        | &check;              |                  |
| Control Signals | $1\ b = 1\ CS$       | $n\ b = 2^n\ CS$ |
| Word size       | Longer               | Shorter          |
| Flexibility     | Less                 | More             |
| Parallelism     | Higher               | Lower            |

- By default, *vertical* microprogramming (CISC) is used
