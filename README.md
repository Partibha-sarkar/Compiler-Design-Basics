# Compiler-Design-Basics

COMPANY : CODTECH IT SOLUTIONS

NAME : PARTIBHA SARKAR

INTERN ID : CT04DH2706

DOMAIN : C++ PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

#DISCRIPTION

This C++ program evaluates arithmetic expressions entered by the user, handling operator precedence, parentheses, and decimal numbers. It uses a stack-based evaluation approach similar to the Shunting Yard algorithm.

Features

Supports basic arithmetic operators: +, -, *, /

Correctly follows operator precedence

Handles parentheses for grouped expressions

Accepts floating-point numbers

Detects division by zero

Ignores whitespace in the input


How It Works

The program uses:

Two stacks:

One for numbers (values)

One for operators (ops)


On reading the expression:

Numbers are pushed to the values stack

Operators are pushed to the ops stack after resolving higher/equal precedence

Parentheses are handled by evaluating enclosed operations first


After the scan, all remaining operations are applied, and the result is displayed.


Example Usage

Enter an arithmetic expression: 3 + 5 * (2 - 8) / 2
Result: -12

*OUTPUT*

<img width="687" height="133" alt="Image" src="https://github.com/user-attachments/assets/6aab96cd-fa85-447e-84a8-2f3c019d7935" />


