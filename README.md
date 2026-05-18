# Python Learning Journey

A beginner-friendly Python learning repository covering core programming concepts from variables to loops. This repository contains chapter-wise notebooks and practice exercises created during the learning process.

---

# Repository Structure

## Chapter 1 — Introduction to Python
**File:** `chap_1.py`

### Topics Covered
- First Python program
- Print statements
- Installing packages using `pip`
- Python modules
- Using the `pyjokes` module
- Basic Python syntax

### Example
```python
print("Hello World")
```

```python
import pyjokes

joke = pyjokes.get_joke()
print(joke)
```

---

## Chapter 2 — Variables, Data Types & Operators
**File:** `chap_2.ipynb`

### Topics Covered
- Variables in Python
- Data types
- Variable naming rules
- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators

### Concepts Included
- Integers
- Floating point numbers
- Strings
- Boolean values
- Mathematical operations

### Example
```python
a = 10
b = 5

print(a + b)
```

---

## Chapter 3 — Strings in Python
**File:** `chap_3.ipynb`

### Topics Covered
- Introduction to strings
- String indexing
- String slicing
- String functions
- Escape sequence characters
- String length

### Important Concepts
- `len()`
- String manipulation
- Uppercase/lowercase conversion
- Escape characters like `\n` and `\t`

### Example
```python
name = "Abeer Ullah Danish"

print(len(name))
```

---

## Chapter 4 — Lists & Tuples
**File:** `chap_4.ipynb`

### Lists
- Creating lists
- Accessing list elements
- Updating lists
- List methods
- Sorting lists
- Adding elements

### Tuples
- Creating tuples
- Immutable data structures
- Tuple methods
- Counting values

### Example
```python
friends = ["Apple", "Banana", "Grapes"]

friends.append("Abeer")
```

---

## Chapter 5 — Dictionaries & Sets
**File:** `chap_5.ipynb`

### Dictionaries
- Key-value pairs
- Accessing dictionary values
- Dictionary methods
- Updating dictionaries

### Sets
- Creating sets
- Unique values
- Union operations
- Empty sets

### Practice Exercises Included
- Hindi to English dictionary
- Unique number finder
- Set operations
- Dictionary-based programs

### Example
```python
info = {
    "name": "Abeer Ullah Danish",
    "Age": 23
}
```

---

## Chapter 6 — Conditional Statements
**File:** `Chap_6.ipynb`

### Topics Covered
- `if` statements
- `if-else` conditions
- `if-elif-else` ladder
- Nested conditions
- User input handling

### Practice Programs
- Age checker
- Even/odd checker
- Student result checker
- Spam detection system
- Username length checker

### Example
```python
age = int(input("Enter your age: "))

if age >= 18:
    print("You are eligible")
else:
    print("You are not eligible")
```

---

## Chapter 7 — Loops in Python
**File:** `Chap_7.ipynb`

### While Loops
- Repetition using conditions
- Counter-based loops
- Infinite loop understanding

### For Loops
- Iterating through ranges
- Iterating through lists
- Loop with `else`

### Practice Exercises
- Print numbers from 1–50
- Iterate through lists
- Range-based loops
- Step values in loops

### Example
```python
for i in range(1, 6):
    print(i)
```

---

# Skills Learned

By completing these chapters, the following Python fundamentals are covered:

- Python syntax
- Variables and data types
- Operators
- Strings
- Lists and tuples
- Dictionaries and sets
- Conditional statements
- Loops
- User input handling
- Basic problem solving
- Python modules and packages

---

# Technologies Used

- Python 3
- Google Colab
- Jupyter Notebook

---

# Learning Approach

This repository follows a practical learning approach:

1. Learn theory
2. Understand syntax
3. Practice examples
4. Solve exercises
5. Build programming logic

---

# Practice Focus

The notebooks contain:

- Beginner exercises
- Small coding tasks
- Practice questions
- Logic-building problems
- Syntax demonstrations

---

# Author

## Abeer Ullah Danish

Bachelor of Science in Computer Science  
Specialization in Data Science

### LinkedIn
- https://www.linkedin.com/in/abeer-ullah-danish-a61aa535b

---

# Future Learning Goals

Planned topics to continue:

- Functions
- Object-Oriented Programming
- File Handling
- Exception Handling
- Modules & APIs
- Data Analysis
- Machine Learning
- AI Engineering

---

# How to Run

## Clone the Repository

```bash
git clone <repository-link>
```

## Open Notebook

Use:
- Jupyter Notebook
- VS Code
- Google Colab

---

# Conclusion

This repository represents a structured Python learning journey from beginner concepts to problem-solving practice. Each chapter builds foundational programming knowledge required for software development, data analysis, and future AI engineering studies.
