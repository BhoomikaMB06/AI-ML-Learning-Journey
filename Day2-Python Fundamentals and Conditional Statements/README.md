# Day 2: Python Fundamentals and Conditional Statements
Introduction

Python is a high-level programming language used in software development, data analysis, automation, machine learning, and artificial intelligence. Python allows us to provide instructions to a computer using simple and readable syntax.
## 1. Variables
Variables store values that can be used throughout a program.
name = "Bhoomika"
age = 21
marks = 85.5
## 2. Data Types
Python provides different data types, such as:
- int: Whole numbers
- float: Decimal numbers
- str: Text
- bool: True or False values
- list: Ordered, changeable collection
- tuple: Ordered, unchangeable collection
- dict: Key-value pairs
- set: Collection of unique values
## 3. Input and Output
The input() function accepts information from the user, while print() displays output.
```
name = input("Enter your name: ")
print("Hello", name)
```
## 4. Operators
Operators perform calculations and comparisons. Arithmetic operators include +, -, *, and /. Comparison operators include ==, !=, >, and <. Logical operators include and, or, and not.
## 5. Conditional Statements
Conditional statements allow a program to make decisions.

### If statement:
```
age = 20

if age >= 18:
    print("Adult")
```
### If-else statement:
```
marks = 75

if marks >= 35:
    print("Pass")
else:
    print("Fail")
```
###If-elif-else statement:
```
marks = 82

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
else:
    print("Grade C or below")
```
# 6. Additional Fundamentals
- Conditions: Expressions that evaluate to True or False.
- Indentation: Spaces that define code blocks in Python.
- Comments: Explanations written using the # symbol.
- Type conversion: Changing a value from one type to another.
- Algorithms: Step-by-step instructions to solve a problem.
- Debugging: Finding and fixing errors in a program.
- Lists and dictionaries: Structures used to organize data.
# 7. Practical Application
Python conditions can create a basic alert for emergency department patient arrivals. This helps demonstrate decision logic before learning how machine learning models forecast future arrivals.

## 8. Structured Data and Unstructured Data

Data is information collected from different sources. In Data Science, Machine Learning, and Artificial Intelligence, data is commonly classified into structured data and unstructured data.

### 8.1 Structured Data

Structured data is information organized in a predefined format, usually in rows and columns. Each column represents a specific attribute, and each row represents a record.

**Example: Student Dataset**

| Student_ID | Name | Age | Marks |
|---|---|---|---|
| 101 | Ravi | 20 | 85 |
| 102 | Anu | 21 | 90 |
| 103 | Priya | 19 | 78 |

In this dataset:
- Each row represents one student.
- Each column represents an attribute, such as name, age, or marks.
- Each cell contains an individual value.

**Examples of structured data:**
- Student records
- Hospital patient records
- Banking transactions
- Sales reports
- Employee information
- Excel spreadsheets and relational database tables

**Advantages of structured data:**
- Easy to organize and understand.
- Easy to search, filter, and sort.
- Can be analyzed using SQL, Python, and Excel.
- Useful for statistical analysis and Machine Learning.

**Python example:**

```python
import pandas as pd

data = {
    "Name": ["Ravi", "Anu", "Priya"],
    "Age": [20, 21, 19],
    "Marks": [85, 90, 78]
}

df = pd.DataFrame(data)

print(df)
print(df["Marks"].mean())
```

This program creates a structured dataset using Pandas and calculates the average marks.

### 8.2 Unstructured Data

Unstructured data is information that does not follow a fixed tabular format or predefined structure.

It may contain text, images, audio, video, or other complex information.

**Examples of unstructured data:**
- Images and photographs
- Videos
- Audio recordings
- Emails and documents
- Social media posts
- Medical X-ray images
- Patient feedback written in natural language

**Advantages of unstructured data:**
- Contains rich information about real-world situations.
- Can capture details that are difficult to represent in simple tables.
- Useful for Natural Language Processing (NLP), computer vision, and generative AI.

**Example:**

A hospital receives the following patient feedback:

"The waiting time was too long, and the emergency department was crowded."

This is unstructured text because it is a sentence rather than a predefined table of individual fields.

Machine Learning and NLP techniques can analyze such text to identify complaints, emotions, and common concerns.

### 8.3 Difference Between Structured and Unstructured Data

| Feature | Structured Data | Unstructured Data |
|---|---|---|
| Format | Organized rows and columns | No fixed tabular format |
| Organization | Predefined schema | Often requires processing |
| Examples | Excel tables, SQL databases | Images, audio, documents |
| Common tools | SQL, Pandas, Excel | NLP, computer vision, deep learning |
| Analysis | Often easier to query | Often requires specialized methods |
| ML applications | Prediction and classification | Text, image, and audio analysis |

### 8.4 What Is Semi-Structured Data?

Semi-structured data does not follow a rigid table format, but it contains labels, keys, tags, or other organizational information.

**Examples:**
- JSON files
- XML documents
- Many application log files
- Web API responses

**Python example:**

```python
import json

data = {
    "patient_id": 101,
    "name": "Ravi",
    "department": "Emergency"
}

json_data = json.dumps(data)

print(json_data)
```

Here, JSON organizes information using key-value pairs without requiring a traditional table.

### 8.5 Data Types in an Emergency Department Project

In the project "Emergency Department Patient Arrival Forecasting Using Machine Learning", we may work with several kinds of data.

**Structured data:**

| Date | Hour | Patient_Arrivals |
|---|---|---:|
| 2026-10-01 | 08:00 | 12 |
| 2026-10-01 | 09:00 | 18 |
| 2026-10-01 | 10:00 | 15 |

This information can be used to study arrival patterns and train a time-series forecasting model.

**Unstructured data:**
- News reports about earthquakes or floods.
- Written incident reports.
- Emergency call recordings.
- Images or videos related to a disaster.

These sources may provide additional context about unusual events, although they need appropriate processing and reliable timestamps before being used in a forecasting system.

**Semi-structured data:**
- Weather API responses.
- Emergency incident feeds in JSON format.
- Timestamped system logs.

### 8.6 How Python Helps Process Data

Python provides libraries for handling different types of data.

- **Pandas:** Reads and analyzes structured tabular data.
- **NumPy:** Performs numerical calculations.
- **JSON:** Handles semi-structured JSON information.
- **OpenCV:** Processes images and video.
- **Natural Language Processing (NLP) tools:** Process and analyze text.
- **Deep Learning libraries:** Can learn patterns from images, text, audio, and other data.

### 8.7 Key Takeaways

- Structured data follows a predefined organization, commonly rows and columns.
- Unstructured data includes information such as images, videos, audio, and free-form text.
- Semi-structured data uses elements such as keys, tags, or labels to organize information.
- Different data types require different storage, processing, and analysis techniques.
- Understanding data is an important first step before building a Machine Learning model.

Conclusion
Python fundamentals are the foundation for data analysis, machine learning, and AI. Understanding variables, data types, operators, conditions, and data structures will make it easier to learn loops, functions, and dataset processing in the next lessons.               its add the data structured  to info
