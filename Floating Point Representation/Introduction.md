# Introduction to Floating Point

- The value of integral and decimal digits are determined as $2^n$ and $2^{-n}$
respectively

- Here, `n` increases from left to right for decimal and right to left for integral
digits

- Moreover, `n` is a natural number for decimal and a whole number for integral
digits

- For example, $2$ will be `01.00` and $2.25$ will be `10.01`

- A floating point number has the following three components:

    1. Sign bit

    2. Exponent

    3. Mantissa

## Steps to Represent a Number in Floating Point

1. Determine the sign of the number

2. Calculate the Mantissa by normalizing the number

    - Express the number in scientific format ($\text{coefficient} \times{2^{exp}}$)

      - The base is always $2$ and the integer part is always $1$

    - The digits after the decimal represents the Mantissa (as the integer part
    is always $1$, it is implicit)

    - The extra bits will be added after this number

3. Calculate the normalized Exponent by adding the bias of the data type to it

4. Convert the biased Exponent into binary

5. Now, combine the three components to form the number
