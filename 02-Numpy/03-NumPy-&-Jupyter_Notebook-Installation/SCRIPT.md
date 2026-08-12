# Lecture 03 – Installing Jupyter Notebook & NumPy

## Introduction

Hello everyone, I am Amash, and welcome back to **Data Science for Beginners**.

In the previous lecture, we learned the fundamentals of NumPy. We discussed what NumPy is, why it is important, and why it is widely used in Data Science.

Now it is time to move from theory to practice.

Before we start writing actual NumPy programs, we first need to prepare our working environment.

In this lecture, we will set up Jupyter Notebook and NumPy on our system. We will also learn the basic Jupyter Notebook workflow so that we are comfortable using it in the upcoming NumPy lectures.

By the end of this lecture, our environment will be ready for actual NumPy programming.

---

# 1. Checking pip

Before installing anything, let's first make sure that `pip` is available on our system.

You may remember that Python has many external libraries and packages. We don't have to manually download every package from the internet.

Python provides a package installer called **pip**.

We can use pip to install packages such as NumPy and Jupyter Notebook.

To check whether pip is available, open the terminal and run:

```bash
pip --version
```

After pressing Enter, the terminal should display the installed pip version.

The exact version may be different on different systems, and that is completely normal.

The important thing is that the command executes successfully and pip is recognized by the system.

So, before moving forward, make sure that pip is working correctly on your computer.

---

# 2. What is Jupyter Notebook?

Now let's understand the main tool we are going to use for our practical Data Science work: **Jupyter Notebook**.

Jupyter Notebook is an interactive environment where we can write and execute Python code.

But what makes it different from a normal Python program?

In a normal Python file, we usually write our program and execute the file.

In Jupyter Notebook, we can divide our work into small sections called **cells**.

We can execute one cell at a time and immediately see its output.

This makes Jupyter Notebook extremely useful for Data Science because Data Science involves a lot of experimentation.

For example, we may want to:

- Load some data.
- Check the data.
- Perform a calculation.
- See the result.
- Modify the code.
- Run it again.
- Add an explanation.
- Continue with the next step.

Jupyter Notebook allows us to do all of this in an interactive environment.

Another important advantage is that we can keep our **code, output, explanations, and documentation together in one notebook**.

That is why Jupyter Notebook is commonly used while learning and working with Data Science, NumPy, Pandas, Matplotlib, and other tools.

---

# 3. Installing Jupyter Notebook

Now that we understand what Jupyter Notebook is, let's install it.

We will use pip for the installation.

Open the terminal and run:

```bash
pip install notebook
```

Then press Enter.

The installation process will begin.

You may see many lines appearing in the terminal while pip downloads and installs the required packages.

Don't worry if you see a lot of text.

The important thing is to wait until the installation process finishes.

Once the installation is completed successfully, we can launch Jupyter Notebook.

---

# 4. Launching Jupyter Notebook

After installing Jupyter Notebook, the next step is to open it.

For that, we use the following command:

```bash
jupyter notebook
```

Press Enter.

Jupyter Notebook will start running, and normally it will open automatically in your default web browser.

You will now see the Jupyter Notebook interface.

It may look slightly different depending on your version or system, but the basic idea remains the same.

This interface will become our practical workspace for the upcoming NumPy lectures.

---

# 5. Understanding the Jupyter Notebook Interface

Once Jupyter Notebook opens, we can see the files and folders available in our current working directory.

From here, we can:

- Navigate through folders.
- Open existing notebooks.
- Create new notebooks.
- Create folders.
- Manage our practical files.

For our course, we want to maintain a clean and organized structure.

As we move forward, we will keep our NumPy notebooks together so that every practical lecture remains easy to find.

---

# 6. Creating a New Python Notebook

Now let's create our first Python Notebook.

Inside Jupyter Notebook, use the option to create a new notebook and select the available **Python 3** environment.

A new notebook will open.

This notebook is where we will write and execute our Python and NumPy code.

We should also give our notebook a meaningful name.

For example:

```text
NumPy-Lecture-03
```

or:

```text
03-NumPy-Setup
```

Using meaningful names is important because we will create many notebooks throughout this course.

If we give every notebook a proper name from the beginning, our files will remain organized later.

---

# 7. What is a Jupyter Notebook File?

A Jupyter Notebook is saved with the `.ipynb` extension.

For example:

```text
03-NumPy-Setup.ipynb
```

The `.ipynb` file contains our notebook information, including:

- Code Cells
- Markdown Cells
- Outputs
- Explanations
- Notebook content

So whenever you see a file ending with `.ipynb`, you can recognize it as a Jupyter Notebook file.

---

# 8. Understanding Cells

Now let's understand one of the most important concepts in Jupyter Notebook: **Cells**.

A cell is an individual block where we can write content.

Instead of writing everything in one large program, we can divide our work into multiple cells.

For example, one cell can contain a Python calculation.

Another cell can contain another calculation.

Another cell can contain an explanation.

This makes our work much easier to understand and manage.

We can also execute cells independently.

This cell-based workflow is one of the main reasons why Jupyter Notebook is so useful for Data Science.

---

# 9. Code Cells

The first important type of cell is the **Code Cell**.

A Code Cell is used to write and execute Python code.

For example:

```python
print("Hello, Data Science!")
```

When we run this cell, the Python code is executed and the output appears below the cell.

This means we can write a small piece of code, execute it, immediately see the result, and then continue with the next piece of code.

This interactive approach will be extremely useful when we start working with NumPy arrays and calculations.

---

# 10. Markdown Cells

The second important type of cell is the **Markdown Cell**.

A Markdown Cell is not used for executing Python code.

Instead, it is used to write text, explanations, headings, notes, and documentation.

For example, we can write:

```markdown
# NumPy Introduction
```

After running the Markdown Cell, it will appear as a properly formatted heading.

We can use Markdown Cells to organize our notebook.

For example:

```markdown
# NumPy Introduction

## Installing NumPy

## Importing NumPy

## NumPy Arrays
```

This allows us to create notebooks that are not just collections of code, but properly structured learning and documentation resources.

---

# 11. Difference Between Code Cell and Markdown Cell

Let's quickly understand the difference.

A **Code Cell** is used to execute Python code.

For example:

```python
print("Hello")
```

A **Markdown Cell** is used to write explanations and documentation.

For example:

```markdown
# Introduction to NumPy
```

So remember:

**Code Cell → Python Code**

**Markdown Cell → Text, Headings, Notes, and Documentation**

We will use both types of cells throughout the Data Science course.

---

# 12. Running a Cell

Now let's learn how to execute a cell.

One of the most useful keyboard shortcuts in Jupyter Notebook is:

```text
Shift + Enter
```

When we press **Shift + Enter**, the selected cell is executed.

If it is a Code Cell, the Python code will run and the output will appear.

If it is a Markdown Cell, the Markdown content will be rendered and displayed in its formatted form.

The notebook will then move to the next cell.

You will use this shortcut very frequently, so it is worth remembering from the beginning.

---

# 13. Installing NumPy

Now our Jupyter Notebook environment is ready.

But we still need to install NumPy.

Remember that Jupyter Notebook and NumPy are two different things.

Jupyter Notebook is our interactive working environment.

NumPy is a Python library that provides powerful tools for numerical computing.

To install NumPy, we will again use pip.

Open the terminal and run:

```bash
pip install numpy
```

Press Enter and wait for the installation to finish.

Once NumPy is installed successfully, we can use it inside our Python Notebook.

---

# 14. Importing NumPy

Installing a library is not enough.

After installation, we need to import the library into our Python program before we can use it.

Open your Jupyter Notebook and create a Code Cell.

Write:

```python
import numpy as np
```

Now press:

```text
Shift + Enter
```

If no error appears, that means NumPy has been successfully imported.

Let's understand this line.

```python
import numpy as np
```

Here, `numpy` is the name of the library.

The `as np` part gives NumPy a shorter name, or alias.

Instead of writing `numpy` every time, we can use `np`.

For example:

```python
np
```

or later:

```python
np.array()
```

This is the standard and commonly used convention when working with NumPy.

You will see `np` throughout almost every NumPy program.

---

# 15. Checking the NumPy Version

Now let's verify our NumPy installation.

Create another Code Cell and write:

```python
print(np.__version__)
```

Press:

```text
Shift + Enter
```

The installed NumPy version will be displayed.

For example, you may see something like:

```text
2.x.x
```

The exact version number may be different on your computer.

That is completely fine.

The purpose of this step is to confirm that:

1. NumPy is installed.
2. NumPy can be imported.
3. Python can access NumPy.
4. We can retrieve information from the NumPy package.

If the version is displayed successfully, our NumPy setup is working correctly.

---

# 16. Saving the Notebook

Now let's save our notebook.

It is important to save our work regularly so that we don't lose our progress.

Give the notebook a meaningful name.

For example:

```text
03-NumPy-Setup.ipynb
```

Remember that `.ipynb` is the file extension used by Jupyter Notebook.

This notebook will contain the practical work we performed in this lecture.

---

# 17. Organizing Our Practical Notebooks

As we continue the Data Science course, the number of practical notebooks will increase.

We don't want to keep all of them randomly scattered across the computer.

Instead, we will maintain a proper folder structure.

For example:

```text
Data Science for Beginners
│
├── NumPy
│   ├── Lecture-03-Setup.ipynb
│   ├── Lecture-04-NumPy-Arrays.ipynb
│   ├── Lecture-05-Array-Creation.ipynb
│   └── ...
│
├── Pandas
├── Matplotlib
├── Seaborn
├── Statistics
├── SQL
├── Machine-Learning
└── Deep-Learning
```

The exact structure may grow as the course grows.

The important thing is to maintain a clear and consistent organization.

---

# 18. Final Setup Verification

Before finishing the lecture, let's verify everything one final time.

First, make sure pip is working:

```bash
pip --version
```

Jupyter Notebook should be installed and launch successfully using:

```bash
jupyter notebook
```

NumPy should be installed using:

```bash
pip install numpy
```

Inside the notebook, NumPy should import successfully:

```python
import numpy as np
```

And finally, we should be able to check the version:

```python
print(np.__version__)
```

If all of these steps are working correctly, congratulations.

Your environment is ready for NumPy programming.

---

# 19. What We Have Learned

Let's quickly summarize what we learned in this lecture.

We started by checking `pip`.

Then we learned what Jupyter Notebook is and why it is useful for Data Science.

We installed Jupyter Notebook and learned how to launch it.

We created a new Python Notebook and learned about the `.ipynb` file format.

Then we learned about Jupyter Notebook cells.

We understood the difference between Code Cells and Markdown Cells.

We also learned how to run cells using:

```text
Shift + Enter
```

After that, we installed NumPy using pip.

We imported NumPy using:

```python
import numpy as np
```

And finally, we checked the installed NumPy version using:

```python
print(np.__version__)
```

So our environment is now ready.

---

# 20. Practical Homework

Before moving to the next lecture, make sure you perform these steps yourself.

### Task 1

Check your pip version:

```bash
pip --version
```

### Task 2

Install Jupyter Notebook:

```bash
pip install notebook
```

### Task 3

Launch Jupyter Notebook:

```bash
jupyter notebook
```

### Task 4

Create a new Python Notebook.

### Task 5

Create a Code Cell and run:

```python
print("Hello, Data Science!")
```

### Task 6

Create a Markdown Cell and write:

```markdown
# NumPy Introduction
```

### Task 7

Practice running cells using:

```text
Shift + Enter
```

### Task 8

Install NumPy:

```bash
pip install numpy
```

### Task 9

Import NumPy:

```python
import numpy as np
```

### Task 10

Check the NumPy version:

```python
print(np.__version__)
```

Do not simply watch these steps in the video.

Perform them yourself.

The goal of this practical lecture is to make sure that your own system is ready before we begin actual NumPy programming.

---

# 21. Next Lecture Preview

Now that our environment is ready, we can finally start working with NumPy.

In the next lecture, we will begin with one of the most important concepts in NumPy:

**NumPy Arrays.**

We will understand what an array is, why NumPy uses arrays, and how to create our first NumPy Array.

From the next lecture onward, we will gradually move into actual NumPy programming and practical operations.

---

# Outro

So guys, that brings us to the end of **Lecture 03**.

Today we successfully prepared our Jupyter Notebook and NumPy environment.

We learned how to install and launch Jupyter Notebook, create a notebook, work with Code Cells and Markdown Cells, install NumPy, import NumPy, and verify its version.

Make sure you complete the practical steps yourself before moving forward.

In the next lecture, we will start the real NumPy programming journey with **NumPy Arrays**.

If you found this lecture useful, make sure to like the video, subscribe to the channel, and follow the **Data Science for Beginners** playlist.

I am Amash, and I'll see you in the next lecture.

**Good Bye**