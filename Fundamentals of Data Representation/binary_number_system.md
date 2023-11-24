# Binary Number System

## Signed and Unsigned Binary

- unsigned binary is binary that does not use two's complement or similar
- binary can represent negative numbers using two's complement, this is where
  the most significant bit is negated, for example the 8 bit 2's complement
  binary number 10001001  
  in decimal is -128 + 8 + 1 = -119  
  if the most significant bit is 0 you can treat the rest of the number as an
  unsigned number.
- the range of an unsigned binary number is 0 to $2^{n}-1$ where n is the number
  of bits
- the range of a signed binary number is $-2^{n-1}$ to $2^{n-1}-1$ where n is
  the number of bits

### Conversion

- to convert from unsigned binary to decimal you can add the value of each bit
  position that is 1
- to convert from decimal to unsigned binary you can subtract the value of each
  bit position from the decimal number and place a 1 if the result is >= 0
- to convert from signed binary to decimal you can add the value of each bit
  position that is 1, rembering to negate the value of the most significant
  bit
- to convert from decimal to signed binary you can convert the number to
  unsigned binary, ignoring the sign, then flip all the bits and add 1.

## Addition

- addition in binary is the same as addition in decimal except you can only
  carry a 1 or a 0
- here is an example of binary addition  

    ```text
    0010
    0111
    ----
    1001
    ```

## Subtraction

- to subtract in binary, you can conver the number you are subtracting to
  negative binary and then add it to the first number, this can be done by
  flipping all the bits and adding 1
- here is an example of binary subtraction  (7 - 2)

  2 as unsigned binary is 0010
  2 as a negative signed binary is 1110

    ```text
    0111
    1110
    ----
    0101 (ignore the carry bit)
    ```

## Multiplication

- multiplication in binary is the same as multiplication in decimal except you
  can only carry a 1 or a 0
- here is an example of binary multiplication (2 * 7)

    ```text
    00010
    00111
    -----
    00010
    00100
    01000
    -----
    01110
    ```

- the first number is shifted left by one bit for each 1 in the second number
- the shifted numbers are then added together

## Fixed Point Representation

- fixed point representation is where a number is represented by a fixed number
  of bits before and after the decimal point
- for example 8 bits could be used to represent the number 3.75:
  
    ```text
    0011.1100
    ```

- in this example, there are 4 bits before the decimal point and 4 bits after
  the decimal point
  
### Conversion

- to convert from decimal to fixed point binary you can multiply the decimal
  number by 2 until you get a whole number, then you can convert this whole
  number to binary and place the decimal point in the correct, if you multiplied
  by 2 n times, there will be n bits after the decimal point. for example, to
  convert the number 8.375 into binary, you do the following:
  
  ```text
  8.375 * 2 = 16.75 (1)
  16.75 * 2 = 33.5 (2)
  33.5 * 2 = 67 (3)
  67 = 1000011
  now place the decimal point in the correct place
  1000.011 (3 bits after the decimal point)
  ```

- to convert a negative decimal number to a fixed point binary number you can
  do a similar process to the one above, but first you need to add the next
  power of 2 to the number until it is positive, then you can convert that to a
  fixed point binary number, then at the end just make sure to set that power of
  2s place to 1, for example, to convert -8.375 into binary, you do the
  following:

  ```text
  -8.375 + 16 = 7.625
  7.625 * 2 = 15.25 (1)
  15.25 * 2 = 30.5 (2)
  30.5 * 2 = 61 (3)
  61 = 111101
  now place the decimal point in the correct place
  111.101 (3 bits after the decimal point)
  adjust the place values
  -16 008 004 002 001 1/2 1/4 1/8
   0   0   1   1   1 . 1   0   1  
  now set the 16s place to 1
  10111.101
  ```

## Floating Point Representation

### Conversion

### Normalisation

### Underflow and Overflow

## Errors

### Absolute Error

### Relative Error

## Advantages and Disadvantages of Fixed Point and Floating Point

## Specification

| Content | Additional information |
| --- | --- |
| Know the difference between unsigned binary<br>and signed binary. | Students are expected to be able to convert<br>between unsigned binary and decimal and vice<br>versa. |
| Know that in unsigned binary the minimum and<br>maximum values for a given number of bits, n,<br>are 0 and 2n -1 respectively. |  |
| Be able to:<br><ul><li> add two unsigned binary integers<br></li><li> multiply two unsigned binary integers.</li></ul> |  |
| Know that signed binary can be used to<br>represent negative integers and that one<br>possible coding scheme is two’s complement. | This is the only representation of negative<br>integers that will be examined. Students are<br>expected to be able to convert between signed<br>binary and decimal and vice versa. |
| Know how to:<br><ul><li> represent negative and positive integers<br>in two’s complement<br></li><li> perform subtraction using two’s<br>complement<br></li><li> calculate the range of a given number of<br>bits, n.</li></ul> |  |
| Know how numbers with a fractional part can be<br>represented in:<br><ul><li> fixed point form in binary in a given<br>number of bits<br></li><li> floating point form in binary in a given<br>number of bits.</li></ul> | Students are not required to know the Institute<br>of Electrical and Electronic Engineers (IEEE)<br>standard, only to know, understand and be able<br>to use a simplified floating representation<br>consisting of mantissa + exponent. |
| Be able to convert for each representation from:<br><ul><li> decimal to binary of a given number of<br>bits<br></li><li> binary to decimal of a given number of<br>bits.</li></ul> | Exam questions on floating point numbers will<br>use a format in which both the mantissa and<br>exponent are represented using two's<br>complement |
| Know and be able to explain why both fixed<br>point and floating point representation of<br>decimal numbers may be inaccurate. | Use binary fractions. For a real number to be<br>represented exactly by the binary number<br>system, it must be capable of being represented<br>by a binary fraction in the given number of bits.<br>Some values cannot ever be represented<br>exactly, for example 0.110. |
| Be able to calculate the absolute error of<br>numerical data stored and processed in<br>computer systems. |  |
| Be able to calculate the relative error of<br>numerical data stored and processed in<br>computer systems. |  |
| Compare absolute and relative errors for large<br>and small magnitude numbers, and numbers<br>close to one. |  |
| Compare the advantages and disadvantages of<br>fixed point and floating point forms in terms of<br>range, precision and speed of calculation |  |
| Know why floating point numbers are<br>normalised and be able to normalise un-<br>normalised floating point numbers with positive<br>or negative mantissas. |  |
| Explain underflow and overflow and describe<br>the circumstances in which they occur. |  |
