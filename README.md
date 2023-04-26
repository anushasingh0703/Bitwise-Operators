# Bitwise-Operators
# Bitwise Operations

In the arithmetic-logic unit (which is within the CPU), mathematical operations like: addition, subtraction, 
multiplication and division are done in bit-level. To perform bit-level operations in C programming, 
bitwise operators are used.

## Basic Bitwise Operators


![bitwise](https://user-images.githubusercontent.com/124857399/234102005-55e1b801-e599-4d4e-b44b-8e403e05e24d.png)


### Bitwise AND Operator (&)

The output of bitwise AND is 1 if the corresponding bits of two operands is 1. 
If either bit of an operand is 0, the result of corresponding bit is evaluated to 0.

In C Programming, the bitwise AND operator is denoted by &.

### Bitwise OR Operator (|)

The output of bitwise OR is 1 if at least one corresponding bit of two operands is 1. 

In C Programming, bitwise OR operator is denoted by |.

### Bitwise XOR (exclusive OR) Operator (^)

The result of bitwise XOR operator is 1 if the corresponding bits of two operands are opposite. 

In C Programming, it is denoted by ^.

### Bitwise Complement Operator ~

Bitwise complement operator is a unary operator (works on only one operand). 
It changes 1 to 0 and 0 to 1. 

In C Programming, it is denoted by ~.

## Shift Operators in C programming


#### 1. Right Shift Operator

Right shift operator shifts all bits towards right by certain number of specified bits. 

It is denoted by >>.


#### 2. Left Shift Operator

Left shift operator shifts all bits towards left by a certain number of specified bits. 
The bit positions that have been vacated by the left shift operator are filled with 0. 

It is denoted by  <<.

