# Python Operators

1. Introduction

Operators in Python are special symbols or keywords used to perform operations on values and variables.

Example:

a = 10
b = 5
print(a + b)

Output:

15

Here, "a" and "b" are operands, "+" is the operator, and "15" is the result.

2. Types of Operators

Python has seven main categories of operators:

1. Arithmetic operators
2. Comparison operators
3. Assignment operators
4. Logical operators
5. Bitwise operators
6. Membership operators
7. Identity operators

3. Arithmetic Operators

Arithmetic operators perform mathematical calculations.

Operator| Description| Example
"+"| Addition| "10 + 5 = 15"
"-"| Subtraction| "10 - 5 = 5"
"*"| Multiplication| "10 * 5 = 50"
"/"| Division| "10 / 5 = 2.0"
"%"| Remainder| "10 % 3 = 1"
"//"| Floor division| "10 // 3 = 3"
"**"| Exponentiation| "2 ** 3 = 8"

a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a // b)
print(a ** b)

4. Comparison Operators

Comparison operators compare two values and return "True" or "False".

- "==": Equal to
- "!=": Not equal to
- ">": Greater than
- "<": Less than
- ">=": Greater than or equal to
- "<=": Less than or equal to

a = 10
b = 5

print(a > b)   # True
print(a < b)   # False
print(a == b)  # False
print(a != b)  # True
print(a >= b)  # True
print(a <= b)  # False

Note: "=" assigns a value; "==" compares values.

5. Assignment Operators

Assignment operators assign or update variable values.

- "=": Assignment
- "+=": Addition assignment
- "-=": Subtraction assignment
- "*=": Multiplication assignment
- "/=": Division assignment
- "//=": Floor division assignment
- "%=": Remainder assignment
- "**=": Exponentiation assignment

x = 10
x += 5
print(x)  # 15

x *= 2
print(x)  # 30

6. Logical Operators

Logical operators combine conditions or reverse Boolean values.

- "and": Both conditions must be true.
- "or": At least one condition must be true.
- "not": Reverses the truth value.

age = 20
has_id = True

print(age >= 18 and has_id)  # True
print(age < 18 or has_id)    # True
print(not has_id)            # False

7. Bitwise Operators

Bitwise operators operate on the binary representation of integers.

- "&": AND
- "|": OR
- "^": XOR
- "~": NOT
- "<<": Left shift
- ">>": Right shift

a = 5
b = 3

print(a & b)   # 1
print(a | b)   # 7
print(a ^ b)   # 6
print(a << 1)  # 10
print(a >> 1)  # 2
print(~a)      # -6

8. Membership Operators

Membership operators check whether an element exists in a collection.

- "in": Element exists.
- "not in": Element does not exist.

languages = ["Python", "Java", "C++"]

print("Python" in languages)     # True
print("Ruby" not in languages)   # True

9. Identity Operators

Identity operators check whether two references point to the same object.

- "is": Same object.
- "is not": Different objects.

a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a == c)  # True: equal values
print(a is b)  # True: same object
print(a is c)  # False: different objects

Use "==" to compare values and "is" to check object identity.

10. Operator Precedence

Operator precedence determines the order of evaluation in an expression.

print(2 + 3 * 4)      # 14
print((2 + 3) * 4)    # 20

Multiplication is evaluated before addition unless parentheses change the order.

11. Practical Applications

Python operators are used for:

- Mathematical calculations
- Comparing student marks
- Checking eligibility conditions
- Updating variables
- Searching for items in collections
- Processing data in algorithms
- Building Machine Learning applications
