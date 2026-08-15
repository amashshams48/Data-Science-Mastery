# 📊 Lecture 04 — NumPy Arrays

Welcome to **Lecture 04** of the **Data Science for Beginners** course.

In this lecture, we begin one of the most important foundations of NumPy — **NumPy Arrays**.

The goal of this lecture is to understand what a NumPy Array is, why arrays are important in Data Science, how NumPy Arrays differ from Python Lists, and how to create basic 1D, 2D, and 3D arrays.

---

## 🎯 Learning Objectives

By the end of this lecture, you will be able to:

- Understand what a NumPy Array is
- Understand why NumPy Arrays are useful in Data Science
- Understand the basic difference between Python Lists and NumPy Arrays
- Create a NumPy Array using `np.array()`
- Understand the concept of a 1D Array
- Understand the concept of a 2D Array
- Understand the basic concept of a 3D Array
- Understand dimensions conceptually
- Understand rows and columns
- Convert a Python List into a NumPy Array
- Visualize the basic structure of 1D, 2D, and 3D Arrays

---

# 📚 Topics Covered

## 1. What is a NumPy Array?

A **NumPy Array** is a structured collection of values provided by NumPy, especially useful for numerical and scientific data.

A simple way to understand it:

**A NumPy Array is a structured collection of values that allows us to work with numerical data efficiently.**

Example:

    import numpy as np

    numbers = np.array([10, 20, 30, 40, 50])

Here:

- `np` is the common alias for NumPy.
- `np.array()` is used to create a NumPy Array.
- `[10, 20, 30, 40, 50]` contains the values.
- `numbers` stores the resulting NumPy Array.

---

## 2. Why Do We Need NumPy Arrays?

Data Science involves working with large amounts of numerical data.

For example, we may work with:

- Student marks
- Daily temperatures
- Product prices
- Sales records
- Sensor measurements
- Scientific measurements
- Machine Learning datasets

If we have only a few values, managing the data is easy.

But imagine working with thousands or millions of numerical values.

We need a structured and organized way to represent this data.

This is where NumPy Arrays become important.

### Why NumPy Arrays?

NumPy Arrays are designed especially for numerical and scientific computing.

They provide a structured way to represent numerical data and form an important foundation for many concepts used later in Data Science.

### Simple Concept

**Lots of Data → Need an Organized Structure → NumPy Arrays**

Think of an Array as an organized container for numerical data.

Example:

    Student Marks

    [78, 85, 91, 67, 88]

This collection of numerical values can be represented using a NumPy Array.

### Key Message

**Data Science works with lots of numerical data, and NumPy Arrays provide an organized structure for representing that data.**

---

## 3. Python List vs NumPy Array

Students already know Python Lists from Python programming.

### Python List

A Python List is a general-purpose collection built into Python.

    marks = [78, 85, 91, 67, 88]

### NumPy Array

A NumPy Array is provided by the NumPy library and is designed especially for numerical and scientific computing.

    import numpy as np

    marks = np.array([78, 85, 91, 67, 88])

### Basic Difference

| Python List | NumPy Array |
|---|---|
| Built into Python | Provided by NumPy |
| General-purpose collection | Designed especially for numerical/scientific data |
| Used throughout Python programming | Widely used in Data Science and scientific computing |

### Important Point

NumPy Arrays do not completely replace Python Lists.

Python Lists are useful for general-purpose programming.

NumPy Arrays become especially useful when working heavily with numerical and scientific data.

---

# 💻 Creating Your First NumPy Array

First, import NumPy:

    import numpy as np

Then create an array:

    numbers = np.array([10, 20, 30, 40, 50])

Print the array:

    print(numbers)

Expected output:

    [10 20 30 40 50]

### Understanding the Code

**`numbers`**

The variable that stores the NumPy Array.

**`np.array()`**

The NumPy function used to create an array.

**`[10, 20, 30, 40, 50]`**

The values that we want to store inside the array.

---

# 1️⃣ Understanding 1D Arrays

A **1D Array (One-Dimensional Array)** is an array where values are arranged in a single line.

Example:

    numbers = np.array([10, 20, 30, 40, 50])

Visual representation:

    [ 10  20  30  40  50 ]

### Simple Concept

**1D Array = One Line**

Example:

    Student Marks

    [78 85 91 67 88]

Another example:

    Temperature Readings

    [31 32 30 29 33]

### Key Point

A 1D Array contains values arranged in one direction or one line.

---

# 2️⃣ Understanding 2D Arrays

A **2D Array (Two-Dimensional Array)** organizes values into **rows and columns**.

Example:

    marks = np.array([
        [80, 85, 90],
        [70, 75, 80],
        [90, 95, 88]
    ])

Visual representation:

    ┌────┬────┬────┐
    │ 80 │ 85 │ 90 │  ← Row 1
    ├────┼────┼────┤
    │ 70 │ 75 │ 80 │  ← Row 2
    ├────┼────┼────┤
    │ 90 │ 95 │ 88 │  ← Row 3
    └────┴────┴────┘

### Row

A **row** is a horizontal arrangement of values.

Example:

    80   85   90

### Column

A **column** is a vertical arrangement of values.

Example:

    80
    70
    90

### Simple Concept

**2D Array = Rows + Columns**

### Real-Life Example

A student marks table can naturally be represented using a 2D Array.

| Student | Math | Science | English |
|---|---:|---:|---:|
| Student 1 | 80 | 85 | 90 |
| Student 2 | 70 | 75 | 80 |
| Student 3 | 90 | 95 | 88 |

---

# 3️⃣ Introduction to 3D Arrays

A **3D Array** can be understood as multiple 2D structures or layers placed together.

### Simple Concept

**1D → One Line**

**2D → Rows + Columns**

**3D → Multiple 2D Layers**

Example:

    Layer 1

    ┌────┬────┐
    │ 10 │ 20 │
    ├────┼────┤
    │ 30 │ 40 │
    └────┴────┘


    Layer 2

    ┌────┬────┐
    │ 50 │ 60 │
    ├────┼────┤
    │ 70 │ 80 │
    └────┴────┘

### Basic Code Example

    data = np.array([
        [
            [10, 20],
            [30, 40]
        ],
        [
            [50, 60],
            [70, 80]
        ]
    ])

At this stage, the purpose is only to understand the structure of a 3D Array.

Detailed 3D operations will be covered later.

---

# 📐 Dimensions, Rows & Columns

Let's connect the concepts of 1D, 2D, and 3D.

## 1D

    [ 10  20  30  40 ]

**One Line**

---

## 2D

    [ 10  20  30 ]
    [ 40  50  60 ]
    [ 70  80  90 ]

**Rows + Columns**

---

## 3D

    Layer 1       Layer 2

    [10 20]       [50 60]
    [30 40]       [70 80]

**Multiple 2D Layers**

### Quick Summary

    1D → Line
    2D → Grid
    3D → Multiple 2D Layers

### Important Terminology

**Dimension** describes the level of structure in which data is arranged.

For this lecture:

- **1D → Single Line**
- **2D → Rows and Columns**
- **3D → Multiple 2D Layers**

> Note: We are learning the conceptual meaning of dimensions in this lecture. NumPy attributes such as `ndim` will be covered separately in a later lecture.

---

# 🔄 Python List → NumPy Array

An existing Python List can be converted into a NumPy Array using `np.array()`.

## Step 1 — Create a Python List

    marks = [78, 85, 91, 67, 88]

## Step 2 — Convert It into a NumPy Array

    import numpy as np

    marks = [78, 85, 91, 67, 88]

    marks_array = np.array(marks)

Conceptually:

    Python List
    [78, 85, 91, 67, 88]

            ↓

        np.array()

            ↓

    NumPy Array
    [78 85 91 67 88]

### 2D List to 2D Array

Python List:

    data = [
        [10, 20, 30],
        [40, 50, 60]
    ]

Convert:

    data_array = np.array(data)

Result:

    [[10 20 30]
     [40 50 60]]

### Key Message

An existing Python List can be converted into a NumPy Array using `np.array()`.

---

# 🎯 Key Takeaways

In this lecture, we learned:

1. What a NumPy Array is
2. Why NumPy Arrays are important for numerical data
3. Python List vs NumPy Array
4. How to create a NumPy Array using `np.array()`
5. What a 1D Array is
6. What a 2D Array is
7. The basic concept of a 3D Array
8. The conceptual meaning of dimensions
9. Rows and columns
10. How to convert a Python List into a NumPy Array

### Core Concept

    NumPy
       ↓
    Arrays
       ↓
    1D → 2D → 3D
       ↓
    Foundation for Data Science

---

# 🚫 Scope of This Lecture

This lecture focuses **only on the fundamental concept and structure of NumPy Arrays**.

The following topics are intentionally reserved for later lectures:

### Array Attributes

- `ndim`
- `shape`
- `size`
- `dtype`
- `itemsize`
- `nbytes`

### Array Creation Functions

- `np.zeros()`
- `np.ones()`
- `np.full()`
- `np.empty()`
- `np.arange()`
- `np.linspace()`

### Random Module

- `np.random`
- Random arrays
- Random numbers
- Random distributions

### Array Indexing

- Positive indexing
- Negative indexing
- Multi-dimensional indexing
- Accessing individual elements

### Array Slicing

- 1D slicing
- 2D slicing
- 3D slicing
- Step-based slicing

### Array Data Types

- Detailed `dtype` explanation
- `astype()`
- NumPy type conversion

### Array Operations

- Addition
- Subtraction
- Multiplication
- Division
- Modulus
- Power
- Comparison operations

### Mathematical Functions

- `np.sum()`
- `np.mean()`
- `np.median()`
- `np.min()`
- `np.max()`
- `np.sqrt()`
- `np.abs()`
- `np.round()`

### Array Reshaping

- `reshape()`
- `resize()`
- `flatten()`
- `ravel()`
- Transpose
- Changing array dimensions

### Array Joining and Splitting

- `concatenate()`
- `stack()`
- `hstack()`
- `vstack()`
- `split()`
- `hsplit()`
- `vsplit()`

### Broadcasting

- Broadcasting rules
- Broadcasting examples
- Advanced broadcasting concepts

### Searching and Sorting

- `np.where()`
- Search-related functions
- Sorting arrays
- `argsort()`

### Copy and View

- `copy()`
- `view()`
- Memory behavior
- Reference behavior

### Advanced Array Concepts

- Vectorization
- Memory optimization
- Advanced multidimensional operations
- Advanced numerical computing

All advanced topics should be reserved for their dedicated lectures.

---

# 🧑‍💻 Practical Examples

## Example 1 — Create a 1D Array

    import numpy as np

    numbers = np.array([10, 20, 30, 40, 50])

    print(numbers)

---

## Example 2 — Create a 2D Array

    import numpy as np

    marks = np.array([
        [80, 85, 90],
        [70, 75, 80],
        [90, 95, 88]
    ])

    print(marks)

---

## Example 3 — Convert a Python List

    import numpy as np

    marks = [78, 85, 91, 67, 88]

    marks_array = np.array(marks)

    print(marks_array)

---

# 📝 Practice Tasks

Try creating the following arrays in Jupyter Notebook.

## Task 1

Create a 1D NumPy Array containing:

    10, 20, 30, 40, 50

---

## Task 2

Create a 2D NumPy Array containing:

    10 20 30
    40 50 60
    70 80 90

---

## Task 3

Create a Python List containing five student marks and convert it into a NumPy Array.

---

# 📂 Lecture Resources

- 🎥 Lecture Video: ([L-02-NumPy_Arrays](https://youtu.be/f2kCJHLiR88))

---

# 🚀 Next Lecture

In the upcoming lectures, we will gradually learn how to work with NumPy Arrays in more detail.

**First understand the structure. Then learn how to work with it.**

---

## 📌 Course

**Data Science for Beginners**

Learn Data Science from the fundamentals and gradually progress toward advanced concepts in Data Science, Machine Learning, and AI.

---

### ⭐ Keep Learning

> **Understand the fundamentals. Practice consistently. Build strong foundations.**