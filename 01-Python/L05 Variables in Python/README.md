# Complete Python Mastery — Lecture 5

## Variables in Python

**Course:** Complete Python Mastery  
**Module:** Module 1 — Python Fundamentals  
**Lecture:** 5  
**Topic:** Variables in Python  
**Format:** Theory + Practical  
**Level:** Complete Beginner

---

## 📚 About This Lecture

This lecture introduces one of the most fundamental concepts in Python programming: **Variables**.

Students learn what a variable is, how a variable stores a value, the mental model of a variable as a **labeled container**, how variables are created using the assignment operator, and the basic rules for naming variables in Python.

The lecture then compares valid and invalid variable names and concludes with a practical transition into VS Code where students create their first variables.

The core idea of the lecture is:

**Variable Name → Stores → Value**

---

## 🎯 Learning Objectives

After completing this lecture, students will be able to:

- Define a variable in Python.
- Understand a variable as a named storage location.
- Explain the relationship between a variable name and its value.
- Create variables using the assignment operator `=`.
- Understand the basic anatomy of a variable assignment.
- Create variables containing different kinds of values.
- Apply Python's variable naming rules.
- Identify valid and invalid variable names.
- Understand why spaces are not allowed in variable names.
- Understand why a variable name cannot start with a number.
- Use underscores in variable names.
- Recognize that Python keywords cannot be used as variable names.
- Apply sensible variable naming practices while writing programs.

---

## 🧠 What is a Variable?

The lecture defines a variable as:

> **A named storage location used to store data.**

A simple mental model is a **labeled container**.

Imagine a container with a label attached to it.

The label tells us what the container represents, while the content inside the container is the value.

For example:

```python
name = "Ali"
```

Here:

- `name` is the variable name.
- `"Ali"` is the value.
- `=` is the assignment operator.

The relationship can be represented as:

**Variable → Stores → Value**

---

## 📦 The Labeled Container Mental Model

A variable can be imagined as a labeled container holding a specific piece of information.

Example:

```python
name = "Ali"
```

Think of it as:

```text
Label: name
Value: "Ali"
```

This mental model helps beginners understand that the variable name gives us a way to refer to stored information in our program.

---

## 🧩 Creating Variables: The Anatomy

The basic structure of variable creation is:

```python
variable_name = value
```

For example:

```python
name = "Ali"
```

The three main components are:

### Variable Name

The name we use to refer to the variable.

Example:

```python
name
```

### Assignment Operator

The `=` symbol assigns the value to the variable.

Example:

```python
=
```

### Value

The data stored in the variable.

Example:

```python
"Ali"
```

More examples from the lecture:

```python
age = 20
city = "Delhi"
country = "India"
```

---

## 📏 Variable Naming Rules

Python variable names must follow specific rules.

### ✅ Allowed

Variable names can contain:

- Letters
- Numbers, but not at the beginning
- Underscores `_`

Examples:

```python
age
student_name
marks2
_city
```

### ❌ Not Allowed

Variable names cannot contain:

- Spaces
- A number at the beginning
- Python keywords
- Hyphens as a substitute for underscores

---

## 🔤 Valid vs Invalid Variable Names

### Valid Names

The lecture provides these examples:

```python
student_name
age
marks2
_city
```

These follow Python's basic naming rules.

### Invalid Names

The lecture provides these examples:

```python
2name
my name
class
total-marks
```

Reasons:

| Variable Name | Why Invalid? |
|---|---|
| `2name` | Cannot start with a number |
| `my name` | Spaces are not allowed |
| `class` | Reserved Python keyword |
| `total-marks` | Hyphens are not underscores |

---

## 🔑 Python Keywords

Python reserves certain words for specific language features.

These reserved words cannot be used as ordinary variable names.

For example:

```python
class
```

is a Python keyword, so it should not be used as a variable name.

The same principle applies to other Python keywords such as `if`.

The important rule is:

**Do not use Python reserved keywords as variable names.**

---

## 🧠 Core Principles

The lecture summarizes the concept with four core principles:

1. **Variables store data.**
2. **Every variable needs a unique name.**
3. **Variable names must follow strict Python rules.**
4. **Variables make programs dynamic and easier to write.**

Variables are essential because programs often need to work with information that can change.

Instead of writing the same value directly throughout a program, we can give the value a meaningful name and work with that variable.

---

## 🧪 Practical Section

The final slide transitions from theory to practical work.

Students are instructed to:

1. Open VS Code.
2. Create or open a Python file.
3. Start creating variables.
4. Use the variable naming rules learned in the lecture.
5. Experiment with simple variable assignments.

Examples based directly on the lecture include:

```python
name = "Ali"
age = 20
city = "Delhi"
country = "India"
```

---

## 📝 Suggested Practice

Students can practice creating variables using meaningful names.

For example:

```python
student_name = "Ali"
age = 20
city = "Delhi"
country = "India"
```

Then identify:

- Variable names
- Assignment operators
- Stored values

Students should also practice identifying whether different variable names are valid or invalid according to Python's rules.

---

## 💡 Key Takeaways

By the end of this lecture, students should understand:

1. A variable is a named storage location used to store data.
2. A variable can be understood as a labeled container.
3. Variables are created using the assignment operator `=`.
4. A variable assignment has a name, an assignment operator, and a value.
5. Variable names can contain letters, numbers, and underscores.
6. A variable name cannot start with a number.
7. Spaces are not allowed in variable names.
8. Python keywords cannot be used as ordinary variable names.
9. Hyphens should not be used in variable names; underscores are used instead.
10. Meaningful variable names make programs easier to understand and work with.

---

## 🗂️ Lecture Structure

| Slide | Topic |
|---:|---|
| 1 | Lesson 05 — Variables in Python |
| 2 | What is a Variable? |
| 3 | The Mental Model: A Labeled Container |
| 4 | Creating Variables: The Anatomy |
| 5 | Variable Naming Rules |
| 6 | Valid vs. Invalid Names |
| 7 | The Core Principles |
| 8 | Let's Start Coding — Creating Our First Variables |

---

## 📌 Prerequisites

Students should have completed:

- **Lecture 1 — Fundamental of Programming**
- **Lecture 2 — Programming Languages**
- **Lecture 3 — Python Installation & Setup**
- **Lecture 4 — VS Code Setup & First Python Program**

Students should have Python and VS Code installed and working before starting the practical section.

---

## 📁 Files

- `05 Python_Variables.pptx` — Lecture presentation
- `README.md` — Lecture documentation
- `script.md` — Detailed slide-by-slide teaching script

---

## 🔜 What's Next?

After learning how variables are created and named, the next stage should build on variables by working with the **different types of data that can be stored in Python variables** and using those values in programs.

---

## 🏆 Course Progress

**Complete Python Mastery**

- [x] Lecture 1 — Fundamental of Programming
- [x] Lecture 2 — Programming Languages
- [x] Lecture 3 — Python Installation & Setup
- [x] Lecture 4 — VS Code Setup & First Python Program
- [x] Lecture 5 — Variables in Python
- [ ] Next Lecture
