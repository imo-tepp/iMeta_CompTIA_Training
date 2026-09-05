# Understanding Number Systems and ASCII

## Learning Objectives

- Convert between decimal, binary and hexadecimal systems.
- Explain the significance of ASCII in computing.
- Describe how hexadecimal is used in technology.

### Decimal

A base 10 number system that uses digits from 0 - 9.

### Binary

A base 2 number system that uses only digits 0 and 1.

### Hexadecimal

A base 16 number system that uses digit 0 - 9 and letters A - F.

- Used in web design for **color codes**
- Facilitates **data representation**
- Helps create **visually appealing content**

### ASCII

ASCII stands for **American Standard Code for Information Interchange**

A character encoding standard for electronic communication where different systems can understand the same text.

## Conversions

The process of changing a number from one system to another.

### Converting Decimal to Binary

1. Identify the decimal number you want to convert.
2. Divide the number by 2 and note the remainder (0 for even, 1 for odd)
3. Continue dividing the quotient by 2 until it reaches 0, recording each remainder.
4. The binary number is formed by reading the remainders from bottom to top.

**Example**: convert 13 to binary

- 13 / 2 = 6.5, remainder is odd(1)
- 6 / 2 = 3, remainder is even(0)
- 3 / 2 = 1.5, remainder is odd(1)
- 1 / 2 = 0.5, remainder is odd(1)

Reading from bottom to top -> 1101

### Converting Binary to Decimal

Binary uses power of 2 on each digit position from right to left. So a Binary number of **1011** is equal to **11**.

```text
Positions  : 3 2 1 0
Power of 2 : 8 4 2 1
Binary     : 1 0 1 1
```

### Converting Decimal to Hexadecimal

1. Divide the decimal number by 16.
2. Record the remainder.
3. Continue dividing the quotient by 16 until it reaches zero.
4. Write the remainders in reverse order to get the hexadecimal value.

**Example**: Convert 255 to hexadecimal

- 255 / 16 = 15, with a remainder of 15 (15 becomes F)
  - 15 * 16 = 240
  - 255 - 240 = 15 (15 is the remainder, becomes F)
- 15 / 16 = 0, with a remainder of 15 (15 becomes F)
  - Can't divide 15, so the remainder is 15 and becomes F

### Converting Hexadecimal to Decimal

**Example**: 5A

- Starting from the rightmost, which is A. A = 10 in hexadecimal.
- 10 x 16 to the power of 0 = 10 x 0 = 10
- 5 x 16 to the power of 1 = 5 x 16 = 80
- 10 + 80 = 90

5A equals to 90 in decimal value.

## Questions & Answers

### 1st Set

1. What is the decimal equivalent of the binary number 1010?
    - 10
2. What is the decimal equivalent of the hexadecimal number 1A?
    - 26
3. What is the binary representation of the decimal number 5?
    - 101
4. Convert the binary number 1111 to decimal?
    - 15
5. What is the decimal equivalent of the binary number 11001?
    - 25
6. Convert the decimal to binary?
    - 11110

### 2nd Set

1. What is the hexadecimal representation of the decimal number 10?
    - A
2. Which of the following is a valid hexadecimal digit?
    - F
3. What is the decimal equivalent of the hexadecimal number 1F?
    - 31
4. How many digits are used in the hexadecimal system?
    - 16
5. Which of the following pairs is equivalent in hexadecimal?
    - 1A and 26
6. What is the hexadecimal number for the decimal number 255?
    - FF
7. In Hexadecimal, what does the letter 'C' represent in decimal?
    - 12
8. What is the hexadecimal value of the decimal number 16?
    - 10
9. What is the sum of the hexadecimal numbers A and 5?
    - F
10. Which of the following is not a hexadecimal number?
    - G12

### 3rd Set

1. What does ASCII stand for?
    - American Standard Code for Information Interchange
2. Which of the following character is represented by the ASCII code 65?
    - A
3. What is the purpose of ASCII?
    - To encode text characters
4. What is the ASCII code for the space character?
    - 32
5. Is the ASCII code for the letter 'A' greater than that for the the letter 'B'?
    - False
6. True or False: ASCII can represent both letters and numbers.
    - True
7. Which of the following characters is NOT represented in ASCII?
    - Emoji characters.
8. What is the purpose of ASCII?
    - To encode text characters?
9. True or False: ASCII can only represent English character.
    - True
10. What is the decimal value of the ASCII character 'A'?
    - 65