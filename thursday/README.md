### Lab Practice 2
In this task, you are expected to implement two functions that perform bitwise operations and 
determine the bit representations of two floating point numbers. The functions that you have to 
implement are as follows.

1. int fitsBits(int num, int n)

This function accepts two integers as inputs. It checks if num can be represented as an n-bit two's complement integer. The function returns 1 if it can, else the function returns 0. For example, fitsBits(5,3) = 0
because the range of values that can be represented by 3-bit signed integer is [-4,3].

2. int bitParity16bit(int input)

This function accepts a 16-bit unsigned number as an input. It returns 1 if the input number has 
an odd number of 1-bits, and returns 0 if the number of 1-bits is even. For example, 
bitParity8bit(7) = 1 because 7 is 0b111 in bits, and therefore, has 3 1-bits (odd). Another example
is bitParity8bit(17) = 0 because 17 is 0b10001, and has 2 1-bits (even).

Please note that you are not allowed to use loop statements in any of these functions. 

In addition to writing these functions, you also have to determine the bit representations of 
-0.75 and 240 based on the 8-bit floating representation in the page 6 of lecture 6 slides, 
and write the values of the bit representations as 1-byte hexadecimal numbers. In this 8-bit 
representation, 1 bit is allocated for sign, 4 bits are for exponent, and 3 bits are for fraction.

### Install command
`make install`

### Run command
`make test`
