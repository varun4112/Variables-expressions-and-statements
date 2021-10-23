# Variables-expressions-and-statements
week1

2.1 Values and types
A value is one of the basic things a program works with, like a letter or a number
These values belong to different types: 2 is an integer, and “Hello, World!” is a
string, so called because it contains a “string” of letters

The print statement also works for integers. We use the python command to start
the interpreter.
python

>>> print(4)

4

2.2 Variables

. A variable is a name that refers to a value.
>>> message = 'And now for something completely different'

>>> n = 17


>>> pi = 3.1415926535897931


This example makes three assignments. The first assigns a string to a new variable
named message; the second assigns the integer 17 to n; the third assigns the
(approximate) value of π to pi.

2.3 Variable names and keywords
Variable names can be arbitrarily long. They can contain both letters and numbers,
but they cannot start with a number. It is legal to use uppercase letters, but it is
a good idea to begin variable names with a lowercase letter

The underscore character ( _ ) can appear in a name. It is often used in names with
multiple words, such as my_name or airspeed_of_unladen_swallow

If you give a variable an illegal name, you get a syntax error:
>>> 76trombones = 'big parade'


SyntaxError: invalid syntax

76trombones is illegal because it begins with a number. more@ is illegal because
it contains an illegal character

Python reserves 35 keywords:
and del from None True
as elif global nonlocal try
assert else if not while
break except import or with
class False in pass yield
continue finally is raise async
def for lambda return await

2.4 Statements
A statement is a unit of code that the Python interpreter can execute

2.5 Operators and operands
Operators are special symbols that represent computations like addition and multiplication. The values the operator is applied to are called operands.
The operators +, -, *, /, and ** perform addition, subtraction, multiplication,
division, and exponentiation.

2.6 Expressions
An expression is a combination of values, variables, and operators. A value all by
itself is considered an expression, and so is a variable

17
x
x + 17

2.8 Modulus operator
The modulus operator works on integers and yields the remainder when the first
operand is divided by the second. In Python, the modulus operator is a percent
sign (%). The syntax is the same as for other operators:

>>> quotient = 7 // 3
>>> print(quotient)

2

>>> remainder = 7 % 3
>>> print(remainder)

1

2.9 String operations
The + operator works with strings, but it is not addition in the mathematical sense.
Instead it performs concatenation, which means joining the strings by linking them
end to end. For example:

>>> first = 10
>>> second = 15
>>> print(first+second)

25

>>> first = '100'
>>> second = '150'
>>> print(first + second)

100150

2.10 Asking the user for input
Sometimes we would like to take the value for a variable from the user via their
keyboard. Python provides a built-in function called input that gets input from
the keyboard1
 When this function is called, the program stops and waits for the
user to type something. When the user presses Return or Enter, the program
resumes and input returns what the user typed as a string.


2.11 Comments
As programs get bigger and more complicated, they get more difficult to read.
Formal languages are dense, and it is often difficult to look at a piece of code and
figure out what it is doing, or why.
For this reason, it is a good idea to add notes to your programs to explain in
natural language what the program is doing. These notes are called comments,
and in Python they start with the # symbol:

compute the percentage of the hour that has elapsed

percentage = (minute * 100) / 60

2.12 Choosing mnemonic variable names
The word
mnemonic2 means “memory aid”. We choose mnemonic variable names to help us
remember why we created the variable in the first place

2.13 Debugging
For syntax errors, the error messages don’t help much. The most common messages
are SyntaxError: invalid syntax and SyntaxError: invalid token, neither
of which is very informative.

