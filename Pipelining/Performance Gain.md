# Performance Gain or Speed-up Factor

$S = {\text{Performance with pipelining} \over{\text{Performance w/o pipelining}}}$

$S = {{1\over{ET_{pipeline}}}\over{1\over{ET_non-pipeline}}}$

$$
\therefore{S = {n t_n \over{k + (n - 1) t_p}}}
$$

- Here `S` is the *performance gained* from using pipelining

- As `n` grows larger than `k`, the performance gain reaches $t_n \over t_p$

- Moreover, **throughput** (rate of output) will be $n \over{[k + (n - 1)] t_p}$

- We consider $S = {t_n\over{t_p}}$ and $throughput = {1 \over{t_p}}$ when either

  - `n` is very large,

  - the value of `n` is not given, or

  - in ideal case

- Whereas, the efficiency is calculated as, $\eta = {S\over{k}}$

- In ideal case, each stage of an instruction consumes equal cycles to finish

  - Therefore, $t_n = k \times{t_p}$
