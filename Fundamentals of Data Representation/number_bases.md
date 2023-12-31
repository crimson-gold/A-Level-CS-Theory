# Number Bases

## Bases

### decimal

- decimal is base 10 and uses digits 0-9 to represent numbers here are some
  examples of decimal numbers  
`[12, 3, 31.65, -4]`

### hexadecimal

- hexadecimal is base 16 and uses digits 0-F to represent numbers 0-15 here are
  some examples of hexadecimal numbers  
`[21, F3, AB3F, 10]`

### binary

- binary is base 2 and uses digits 0-1 to represent numbers, computers can be
  represented in computers by high(1) or low(0) current. here are some examples
  of binary numbers  
`[10, 0110, 11010011, 0101110101010101]`

- see [binary_number_system.md](binary_number_system.md) for more information on
  binary numbers

## Conversion

you can convert binary to decimal by adding binary places as decimal numbers
for example binary number 10110001 in decimal would be  
128 + 32 + 16 + 1 = 177  

to convert decimal to binary you can work from left to right subtracting the
value of each position in the binary number from the decimal number and placing
a 1 if the result of the calculation is > 0  
for example 85 as an 8 bit binary number  

128 > 85, 85 - 64 = 21 (add 1 to 7th place), 32 > 21, 21 - 16 = 5 (add 1 to 5th
place), 8 > 5, 5 - 4 = 1 (add 1 to 3rd place), 2 > 1, 1 - 1 = 0 (add 1 to 1st
place)  
the result of this conversion should be 01010101

to convert binary to hexadecimal you split the bits by nibbles (4 bits) for
example  
101001110111110  
101|0011|1011|1110  
2 + 4 + 8 = 14 (E)  
1 + 2 + 8 = 11 (B)  
1 + 2 = 3  (3)  
1 + 4 = 5 (5)  
so our hex number is 53BE (in decimal this would be 21438)
to convert hexadecimal back to binary you just turn your hex digits into nibbles
and merge them back together in the appropriate order  

## Specification

| Content | Additional information |
| --- | --- |
| Be familiar with the concept of a number base,<br>in particular:<br><ul><li> decimal (base 10)<br></li><li> binary (base 2)<br></li><li> hexadecimal (base 16).</li></ul> | Students should be familiar with expressing a<br>number’s base using a subscript as follows:<br>Base 10: Number<sub>10</sub>, eg 67<sub>10</sub><br>Base 2: Number<sub>2</sub>, eg 10011011<sub>2</sub><br>Base 16: Number<sub>16</sub>, eg AE<sub>16</sub> |
| Convert between decimal, binary and<br>hexadecimal number bases. |  |
| Be familiar with, and able to use, hexadecimal<br>as a shorthand for binary and to understand<br>why it is used in this way. |  |
