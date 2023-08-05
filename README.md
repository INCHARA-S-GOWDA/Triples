# Triples
Problem Statement:- Design, develop and implement a C program to generate the machine code using Triples for
the statement A = -B * (C +D) whose intermediate code in three-address form:

T1 = -B

T2 = C + D

T3 = T1 * T2

A = T3


Description:- In computer science and computer architecture, a "three-address form" or "three-address code" is a representation of code or instructions used in intermediate code generation during compilation. It is called "three-address" because each instruction typically involves three memory addresses or operands.
Each instruction has the format:

result = operand1 operator operand2

In intermediate code generation, triples are a way of representing instructions or operations in a three-address code format. Each triple consists of three components: an operator, a source operand (usually denoted as arg1), and a destination operand (usually denoted as result).
The general form of a triple is:

(result, operator, arg1)
