# Lecture 03 – Installing Jupyter Notebook & NumPy

Welcome to **Lecture 03** of the **Data Science for Beginners** course.

In this practical lecture, we prepare our Python environment for learning NumPy. We check `pip`, understand Jupyter Notebook, install and launch Jupyter Notebook, create a new notebook, understand cells and Markdown Cells, install NumPy, import NumPy, and verify the installed NumPy version.

---

## 🎯 Learning Objectives

By the end of this lecture, you will be able to:

- Understand the purpose of `pip`.
- Understand what Jupyter Notebook is.
- Understand why Jupyter Notebook is useful for Data Science.
- Install Jupyter Notebook using `pip`.
- Launch Jupyter Notebook from the terminal.
- Create a new Python Notebook.
- Understand Jupyter Notebook cells.
- Understand Code Cells.
- Understand Markdown Cells.
- Run cells using `Shift + Enter`.
- Install NumPy using `pip`.
- Import NumPy into Python.
- Check the installed NumPy version.
- Save and organize Jupyter Notebook files.

---

## 📚 Topics Covered

### 1. Checking pip

We first check whether `pip` is available on the system.

```bash
pip --version
```

`pip` is a package installer and package management tool used to install and manage Python packages.

---

### 2. What is Jupyter Notebook?

Jupyter Notebook is an interactive environment that allows us to write and execute Python code in separate cells.

It is especially useful for Data Science because we can:

- Write code step by step.
- Execute individual cells.
- View outputs immediately.
- Add explanations and notes.
- Keep code, output, and documentation together.

---

### 3. Installing Jupyter Notebook

Jupyter Notebook can be installed using `pip`.

```bash
pip install notebook
```

This command installs Jupyter Notebook and its required dependencies.

---

### 4. Launching Jupyter Notebook

After installation, Jupyter Notebook can be launched from the terminal using:

```bash
jupyter notebook
```

This starts the Jupyter Notebook environment and normally opens the interface in a web browser.

---

### 5. Creating a New Notebook

After launching Jupyter Notebook, we create a new Python Notebook.

The notebook provides an interactive workspace where Python code can be written and executed.

Jupyter Notebook files use the `.ipynb` extension.

Example:

```text
03-NumPy-Setup.ipynb
```

---

### 6. Understanding Cells

Jupyter Notebook follows a cell-based workflow.

A cell is an individual block where we can write and execute content.

Cells allow us to work with different parts of our code independently.

---

### 7. Code Cells

A **Code Cell** is used to write and execute Python code.

Example:

```python
print("Hello, Data Science!")
```

When the cell is executed, the output is displayed below the cell.

---

### 8. Markdown Cells

A **Markdown Cell** is used to write text and documentation inside the notebook.

Markdown Cells can be used for:

- Headings
- Explanations
- Notes
- Documentation
- Organizing the notebook

Example:

```markdown
# NumPy Introduction
```

Markdown helps make notebooks clean, readable, and properly organized.

---

### 9. Running Cells

The selected cell can be executed using:

```text
Shift + Enter
```

`Shift + Enter` runs the current cell and moves to the next cell.

---

### 10. Installing NumPy

After setting up Jupyter Notebook, we install NumPy separately.

NumPy is a Python library used for numerical computing.

NumPy can be installed using:

```bash
pip install numpy
```

---

### 11. Importing NumPy

After installing NumPy, we import it into our Python Notebook using:

```python
import numpy as np
```

Here:

- `numpy` is the library being imported.
- `np` is the commonly used alias for NumPy.

---

### 12. Checking NumPy Version

After importing NumPy, we verify that the installation is working correctly.

```python
print(np.__version__)
```

This displays the installed NumPy version.

If the version is displayed successfully without an import error, NumPy is ready to use.

---

## 💻 Commands Used in This Lecture

### Check pip

```bash
pip --version
```

### Install Jupyter Notebook

```bash
pip install notebook
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Install NumPy

```bash
pip install numpy
```

### Import NumPy

```python
import numpy as np
```

### Check NumPy Version

```python
print(np.__version__)
```

---

## ⌨️ Important Shortcut

| Shortcut | Purpose |
|---|---|
| `Shift + Enter` | Run the current cell and move to the next cell |

---

## 📁 Jupyter Notebook File

Jupyter Notebook files use the `.ipynb` extension.

Example:

```text
03-NumPy-Setup.ipynb
```

A notebook can contain:

- Code Cells
- Markdown Cells
- Code Outputs
- Explanations
- Documentation

---

## 🎯 Key Takeaways

- `pip` is used to install Python packages.
- Jupyter Notebook provides an interactive environment for Python and Data Science.
- Jupyter Notebook allows us to work with individual cells.
- Code Cells are used to write and execute Python code.
- Markdown Cells are used for headings, explanations, notes, and documentation.
- `Shift + Enter` is used to execute the current cell.
- Jupyter Notebook files use the `.ipynb` extension.
- NumPy can be installed using `pip install numpy`.
- NumPy can be imported using `import numpy as np`.
- `np` is the commonly used alias for NumPy.
- `np.__version__` can be used to check the installed NumPy version.
- The environment is now ready for actual NumPy programming.

---

## 📝 Homework

Complete the following tasks on your own system:

1. Check the `pip` version.
2. Install Jupyter Notebook.
3. Launch Jupyter Notebook.
4. Create a new Python Notebook.
5. Create and run a Code Cell.
6. Create a Markdown Cell.
7. Practice running cells using `Shift + Enter`.
8. Install NumPy.
9. Import NumPy using:

```python
import numpy as np
```

10. Check the NumPy version using:

```python
print(np.__version__)
```

11. Save your notebook properly.

---

## ❓ Practice Questions

1. What is `pip`?
2. What is Jupyter Notebook?
3. Why is Jupyter Notebook useful for Data Science?
4. How do you install Jupyter Notebook?
5. How do you launch Jupyter Notebook?
6. What is a cell in Jupyter Notebook?
7. What is a Code Cell?
8. What is a Markdown Cell?
9. What is the purpose of a Markdown Cell?
10. Which shortcut is used to run a cell?
11. How do you install NumPy?
12. How do you import NumPy?
13. Why do we commonly use `np` as an alias for NumPy?
14. How do you check the installed NumPy version?
15. What is the file extension of a Jupyter Notebook?

---

## 💼 Interview Questions

### Q1. What is Jupyter Notebook?

Jupyter Notebook is an interactive environment used to write and execute code, display outputs, and document programming work.

### Q2. What is pip?

`pip` is a package management tool used to install and manage Python packages.

### Q3. How do you install Jupyter Notebook?

```bash
pip install notebook
```

### Q4. How do you launch Jupyter Notebook?

```bash
jupyter notebook
```

### Q5. What is a Code Cell?

A Code Cell is used to write and execute Python code.

### Q6. What is a Markdown Cell?

A Markdown Cell is used to add headings, explanations, notes, and documentation to a notebook.

### Q7. How do you install NumPy?

```bash
pip install numpy
```

### Q8. How do you import NumPy?

```python
import numpy as np
```

### Q9. Why do we use `np`?

`np` is a commonly used short alias for the NumPy library.

### Q10. How do you check the NumPy version?

```python
print(np.__version__)
```

### Q11. What is the extension of a Jupyter Notebook?

Jupyter Notebook files use the `.ipynb` extension.

---

## 📌 Lecture Summary

In this lecture, we prepared our environment for learning NumPy.

We started by checking `pip` and understanding its purpose.

We then learned what Jupyter Notebook is and why it is useful for Data Science.

After that, we installed Jupyter Notebook using `pip`, launched it from the terminal, and created a new Python Notebook.

We learned about Jupyter Notebook cells, including Code Cells and Markdown Cells. We also learned how to execute cells using the `Shift + Enter` shortcut.

After setting up Jupyter Notebook, we installed NumPy using:

```bash
pip install numpy
```

We then imported NumPy using:

```python
import numpy as np
```

Finally, we verified the NumPy installation using:

```python
print(np.__version__)
```

Our environment is now ready for actual NumPy programming.

---

## 🔜 Next Lecture

### Lecture 04 – NumPy Arrays

In the next lecture, we will begin actual NumPy programming.

We will learn:

- What is a NumPy Array?
- Why NumPy Arrays are important.
- How to create our first NumPy Array.
- Basic practical operations with NumPy Arrays.

---

## 📺 Course Navigation

### ⬅️ Previous Lecture

**Lecture 02 – What is NumPy?**

[▶️ Watch Lecture 02](https://youtu.be/rfExg5xuL4M?si=Z61OFYSMcGnmRYpp)

---

### 📚 Complete Course Playlist

**Data Science for Beginners**

[▶️ Watch Complete Playlist](https://youtube.com/playlist?list=PLBMDK0_xvsu0&si=buUAn9Gclpii7d0U)

---

### 👨‍🏫 Instructor

**Amash Shams**

### Data Science for Beginners