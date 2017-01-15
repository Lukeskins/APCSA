## __Unit 1 - Intro to Java and Number Systems__

*Converting between Hexadecimal, Decimal, and Binary*
***

__Decimal to Binary:__
1. Find the largest multiple of eight in the number.

2. Find the largest 8-bit digit in the decimal number.

3. Write all 8-bit numbers starting with the largest 8-bit digit.

4. For the numbers that go into the remaining amount of the decimal number, write a one.  For the numbers that do not go into it, write a zero.


```
e.g. 279

Largest 8-bit digit in 279 is 256

| 8-bit | Binary |
------------------
|256    |1       |
|128    |0       |
|64     |0       |
|32     |0       |
|16     |1       |
|8      |0       |
|4      |1       |
|2      |1       |
|1      |1       |

279 in binary is 100010111
```

• • •

__Decimal to Hexadecimal:__
1. Find how many times 16<sup>decimal place</sup> goes into the number.  Write that number.

2. Find the remainder of the previous division.  If it is greater than 15, continue to divide by 16<sup>decimal place</sup>.  If it is less than or equal to 15, write the appropriate hex number.

 * 0 through 9 are all written the same.

 * 10 is A, 11 is B, 12 is C, 13 is D, 14 is E, 15 is F.


```
e.g. 74

Divide 74 by 16 = four.  Remainder is 10.

Write four.

Write remainder which is 10 as A.

74 in hexadecimal is 4A
```

• • •

__Binary to Decimal:__

1. Write out binary number.  

2. From the right, right the octal numbers according to length.

3. If it is a zero, do not add to the sum.  If it is a one, add the octal number to the sum.


```
e.g. 100101

100101 has the numbers 32 16 8 4 2 1

Since there is a 1 at the 32 spot, add 32 to the sum.  Continue through the number adding all of the numbers with ones.

100101 in decimal is 37
```

• • •

__Binary to Hexadecimal:__

*insert information here.*

• • •

__Hexadecimal to Decimal:__

*insert information here.*

• • •

__Hexadecimal to Binary:__

*insert information here.*

__Decimal to ASCII:__

*insert information here.*
