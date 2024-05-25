# IEEE 754 Floating Point Representation

## Single Precision

- The single precision representation, also known as the Float data type, is 4
bytes (32 bit) long where:

  - Sign: 1 bit

  - Exponent: 8 bits

  - Mantissa: 23 bits

- The standard float representation uses $127$ as bias

## Double Precision

- The double precision representation, also known as the Double data type, is 8
bytes (64 bit) long where:

  - Sign: 1 bit

  - Exponent: 11 bits

  - Mantissa: 52 bits

- The standard double representation uses $1023$ as bias

## Example

Consider the number $128.75$. Following are the steps to calculate its Float
representation:

1. The number is positive, therefore the sign bit will be $0$

2. The number (`1000 0000.11`) will be normalized as $1.0000 0001 1 \times{2^7}$

3. By adding the bias to the exponent, we get $127 + 7 = 134$

4. The exponent $134$ in binary form is `1000 0110`

5. Therefore, the number will be `0 1000 0110 0000 0001 1000 0000 0000 000`

Similarly, its double representation will be:

`0` `000 1000 0110` `0000 0001 1000 00000000 00000000 00000000 00000000 00000000`
