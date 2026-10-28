Computer Architecture Assignment

Course: Computer Architecture
Topic: Problem Solving – Group 3
Department: Artificial Intelligence and Machine Learning

Question 1: 8-bit 2's Complement Arithmetic

File: "question1_twos_complement.py"

This program performs signed binary arithmetic using the 8-bit 2's complement representation. It displays the operands in binary, performs the arithmetic operations, displays the results in binary and decimal formats, and checks for arithmetic overflow.

(a) (+48) + (+23)

  00110000   (+48)
+ 00010111   (+23)
-----------
  01000111   (+71)

Result: +71
Binary: "01000111"
Arithmetic Overflow: No

(b) (-46) - (-29)

Subtracting −29 is equivalent to adding +29.

  11010010   (-46)
+ 00011101   (+29)
-----------
  11101111   (-17)

Result: −17
Binary: "11101111"
Arithmetic Overflow: No

Question 2: Rotate Right Operations

File: "question2_rotate_operations.py"

This program performs Rotate Right (ROR) and Rotate Right through Carry (RCR) operations on an 8-bit binary number. It displays each rotation step and the final result.

(a) Rotate Right without Carry (ROR)

Original Binary: "11010101"
Number of Positions: 2

Original:    11010101
Rotation 1:  11101010
Rotation 2:  01110101

Final Result: "01110101"

(b) Rotate Right with Carry (RCR)

Original Binary: "11010101"
Number of Positions: 2
Initial Carry: 0

Original:    11010101
Rotation 1:  01101010   Carry = 1
Rotation 2:  10110101   Carry = 0

Final Result: "10110101"
Final Carry: 0

Tecnologies Used
- python 3
- 8-bit 2's Complement Arithmetic, Binary Arithmetic, Rotate Right (ROR), Rotate Right through Carry (RCR), Overflow Detection, Carry Flag


Conclusion

Both Python programs demonstrate 8-bit signed binary arithmetic and binary rotation operations. The program outputs are verified against manual binary calculations, including overflow detection and carry flag updates.
