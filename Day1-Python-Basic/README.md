# Day 1: Introduction to Python Programming

## 1. Introduction to Python

Python is a high-level, general-purpose programming language. It is known for its simple syntax and readability, making it suitable for beginners and professionals.

Python is widely used in:

- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning
- Generative AI
- Data Science and Data Analysis
- Web Development
- Automation

### Importance of Python

Python allows developers to write programs using readable code. It also provides many libraries, such as NumPy, Pandas, Scikit-learn, TensorFlow, and PyTorch, which are useful for data analysis and AI development.

## 2. What Is Artificial Intelligence?

Artificial Intelligence (AI) is a field of computer science focused on creating systems that perform tasks requiring abilities such as reasoning, learning, problem-solving, and decision-making.

**Example:** An AI assistant that answers questions.

## 3. What Is Machine Learning?

Machine Learning (ML) is a branch of AI that enables computers to learn patterns from data and make predictions or decisions.

**Example:** Predicting future hospital patient arrivals using historical patient data.

## 4. What Is Deep Learning?

Deep Learning is a type of Machine Learning that uses neural networks with multiple layers to learn complex patterns from data.

**Example:** Recognizing handwritten digits or identifying objects in images.

## 5. What Is Generative AI?

Generative AI is a type of AI that generates new content, such as text, images, audio, and computer code.

**Example:** An AI chatbot that answers questions or generates a summary of a document.

## 6. First Python Program

The `print()` function displays information on the screen.

```python
print("Hello, World!")
print("Welcome to Python Programming")
print("I am learning AI and Machine Learning")
```

**Output:**

```text
Hello, World!
Welcome to Python Programming
I am learning AI and Machine Learning
```

## 7. Python Comments

Comments are notes written in the code to explain its purpose. Python ignores single-line comments during execution.

The `#` symbol is used to write a single-line comment.

```python
# This is my first Python program

print("Welcome to Day 1")
```

Comments make code easier to understand and maintain.

## 8. Variables in Python

A variable is a name used to store a value in a program.

```python
student_name = "Bhoomika"
age = 21
study_hours = 2

print(student_name)
print(age)
print(study_hours)asd
```

**Output:**

```text
Bhoomika
21
2
```

### Rules for Variables

- A variable name can contain letters, numbers, and underscores.
- A variable name cannot begin with a number.
- Variable names are case-sensitive.
- Use meaningful names to make code readable.
- The `=` operator assigns a value to a variable.

## 9. Python Data Types

Data types describe the kind of value stored in a variable.

| Data type | Description    | Example    |
| --------- | -------------- | ---------- |
| `str`     | Text           | `"Python"` |
| `int`     | Whole number   | `25`       |
| `float`   | Decimal number | `85.5`     |
| `bool`    | True or false  | `True`     |

### Example Program

```python
name = "Python"
age = 21
percentage = 85.5
is_learning = True

print(type(name))
print(type(age))
print(type(percentage))
print(type(is_learning))
```

The `type()` function identifies the data type of a value.

## 10. Input and Output in Python

The `input()` function accepts information from the user. The `print()` function displays information.

```python
name = input("Enter your name: ")

print("Welcome", name)
```

### Taking Numeric Input

The `input()` function returns text. To perform mathematical calculations, convert the input into a number using `int()` or `float()`.

```python
age = int(input("Enter your age: "))

print("Next year your age will be", age + 1)
```

## 11. Python Operators

Operators perform calculations and comparisons.

| Operator | Purpose        | Example  |
| -------- | -------------- | -------- |
| `+`      | Addition       | `10 + 5` |
| `-`      | Subtraction    | `10 - 5` |
| `*`      | Multiplication | `10 * 5` |
| `/`      | Division       | `10 / 5` |
| `%`      | Remainder      | `10 % 3` |
| `**`     | Exponentiation | `2 ** 3` |
| `>`      | Greater than   | `10 > 5` |
| `<`      | Less than      | `3 < 5`  |
| `==`     | Equal to       | `5 == 5` |

### Example Program

```python
a = 10
b = 3

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Remainder:", a % b)
print("Power:", a ** b)
```

## 12. Mini-Project: Hospital Patient Arrival Analysis

This beginner program calculates the average number of patient arrivals over two days and compares the counts.

```python
yesterday = 120
today = 150

average = (yesterday + today) / 2

print("Patients yesterday:", yesterday)
print("Patients today:", today)
print("Average patient arrivals:", average)

if today > yesterday:
    print("Patient arrivals increased.")
elif today < yesterday:
    print("Patient arrivals decreased.")
else:
    print("Patient arrivals stayed the same.")
```

**Output:**

```text
Patients yesterday: 120
Patients today: 150
Average patient arrivals: 135.0
Patient arrivals increased.
```

This is a rule-based Python program, not yet a Machine Learning model. It introduces the programming concepts that will help us build a real patient-arrival forecasting model in the future.


