# Complete Python Mastery — Lecture 4

## Visual Studio Code Setup & First Python Program — Teaching Script

**Course:** Complete Python Mastery  
**Module:** Module 1 — Python Fundamentals  
**Lecture:** 4  
**Topic:** Visual Studio Code Setup & First Python Program  
**Format:** Practical / Hands-On Teaching Script  
**Audience:** Complete Beginners

---

# Introduction

### Script

Good Morning everyone, and welcome back to **Complete Python Mastery**.

In our previous lectures, we built the foundation for learning Python.

First, we understood what programming is and why computers need instructions.

Then, we learned about programming languages and understood where Python fits among different types of programming languages.

After that, we installed Python on our computer and verified that it was working correctly.

So, our computer is now ready for Python.

But there is one more thing we need before we start writing programs regularly.

We need a proper environment where we can create Python files, write our code, run our programs, and see the output.

For this, we are going to use **Visual Studio Code**, commonly known as **VS Code**.

And today, we are going to do two important things:

First, we will set up VS Code for Python development.

And second, we will write and run our **very first Python program**.

By the end of this session, you will have written actual Python code and seen its output on your screen.

So let's begin.

---

# Part 1 — What is Visual Studio Code?

### Script

Before installing anything, let's understand what VS Code actually is.

**Visual Studio Code is a source-code editor.**

In simple words, it is an application that provides us with a comfortable environment for writing and working with code.

You can technically write code in a simple text editor, but a dedicated code editor gives us many useful features.

For example, it helps us organize our files, work with different programming languages, identify syntax problems, and run our programs more conveniently.

Throughout this Python course, VS Code will be our main workspace for writing Python programs.

So you can think of it as our **coding desk**.

Just as a student needs a proper desk and notebook for studying, a programmer needs a suitable development environment for writing and managing code.

---

# Part 2 — Installing Visual Studio Code

### Script

Now let's install VS Code.

First, open your web browser.

We need to download Visual Studio Code from its official source.

Once the download page is open, select the Windows version appropriate for your system.

After the installer has been downloaded, open it.

The installation wizard will guide us through the setup.

Follow the installation steps and allow the installer to complete the process.

Once the installation is finished, launch Visual Studio Code.

If VS Code opens successfully, that means our code editor is ready.

At this point, remember that installing VS Code and installing Python are two different things.

**Python is the programming language and its interpreter.**

**VS Code is the environment in which we can conveniently write and manage our Python code.**

We need both for the workflow we are setting up.

---

# Part 3 — Understanding the VS Code Interface

### Script

Now that VS Code is open, let's take a quick look at what we are seeing.

Don't worry if the interface looks unfamiliar.

We are not going to learn every feature today.

We only need the basic parts required to start Python programming.

One important area is the **Explorer**.

The Explorer helps us view and manage files and folders.

Another important area is the main **Editor**.

This is where we will actually write our Python code.

We also have the **Terminal**, where we can execute commands and interact with our programming environment.

As we continue the course, we will gradually become familiar with these areas.

For now, just remember:

**Explorer → Manage files**

**Editor → Write code**

**Terminal → Run commands and programs**

These three areas will become very important as we progress.

---

# Part 4 — Installing the Python Extension

### Script

Now we need to configure VS Code for Python.

VS Code supports many different programming languages.

To make Python development easier, we install the **Python extension**.

Let's open the **Extensions** section in VS Code.

In the search box, search for:

**Python**

We need to install the appropriate Python extension.

Once the extension is installed, VS Code gains Python-specific features that make working with Python much easier.

For example, the editor can provide Python-aware coding support and help us work with Python files and the Python interpreter.

The important thing to understand is that the extension does not replace Python itself.

We already installed Python in our previous lecture.

The extension simply helps VS Code work effectively with our Python environment.

So our setup now looks like this:

**Python → Executes Python programs**

**VS Code → Provides our coding environment**

**Python Extension → Connects Python development features with VS Code**

---

# Part 5 — Creating Our First Python File

### Script

Now we are ready to create our first Python source file.

A Python program is normally stored in a file with the extension:

```text
.py
```

The `.py` extension tells us that the file contains Python source code.

Let's create a new file.

For our first program, we can name it:

```text
hello.py
```

Notice the `.py` at the end.

This is important.

If you create a file called:

```text
hello.txt
```

that is a text file.

But:

```text
hello.py
```

is recognized as a Python source file.

So from now on, whenever we create Python programs, you will frequently see filenames ending with `.py`.

---

# Part 6 — Writing Our First Python Program

### Script

Now comes the most exciting part.

We are going to write our **first Python program**.

Inside `hello.py`, type:

```python
print("Hello, World!")
```

That's it.

Our first Python program is complete.

It may look extremely simple, but there are already several important concepts here.

We are writing an instruction.

That instruction tells Python to display some text.

Let's understand it.

The word:

```python
print
```

is a built-in Python function.

A function is something we can use to perform a particular task.

In this case, the `print()` function is used to display information as output.

Inside the parentheses, we have:

```python
"Hello, World!"
```

This is a string — a sequence of characters representing text.

The quotation marks tell Python that this is text.

So the complete statement:

```python
print("Hello, World!")
```

means:

**Display the text "Hello, World!" as output.**

---

# Part 7 — Understanding the `print()` Function

### Script

Let's focus a little more on `print()` because this is one of the first Python functions you will use.

The general structure is:

```python
print(...)
```

The `print` function tells Python that we want to display something.

For example:

```python
print("Hello")
```

will display:

```text
Hello
```

And:

```python
print("Welcome to Python")
```

will display:

```text
Welcome to Python
```

So `print()` is useful whenever we want our program to show information to the user.

In our first program:

```python
print("Hello, World!")
```

the text inside the quotation marks is what gets displayed.

For now, you don't need to memorize every detail about functions or strings.

We will study these concepts much more deeply in upcoming lectures.

Today, the goal is simply to understand the basic relationship:

**`print()` → displays output.**

---

# Part 8 — Running the First Python Program

### Script

Now we have written our code, but writing code is only one part of programming.

We also need to **run** the program.

This is where execution comes in.

We can run our Python file from VS Code using the available run option or the Python execution workflow.

When we run the program, Python reads the instructions we have written and executes them.

Our instruction is:

```python
print("Hello, World!")
```

Python processes that instruction.

The result should appear in the output area or terminal.

And we should see:

```text
Hello, World!
```

This is our first complete programming cycle:

**Write Code → Run Program → Get Output**

That simple cycle is something you will repeat again and again throughout this course.

---

# Part 9 — Understanding What Just Happened

### Script

Let's pause for a moment and understand what we just accomplished.

We started with an idea:

**We want the computer to display a message.**

Then we expressed that idea using Python:

```python
print("Hello, World!")
```

We saved the instruction inside a Python file:

```text
hello.py
```

Then we executed the program.

Python processed the instruction and produced the output:

```text
Hello, World!
```

So we have now experienced the programming process that we discussed in our first lecture.

Remember the flow from Lecture 1:

**Problem → Plan → Instructions → Execution → Output**

Here, our task was very simple.

The instruction was written in Python.

Python executed it.

And the result appeared as output.

This is the first time in our course where you are not just learning about programming — you are actually doing it.

---

# Part 10 — Understanding Source Code and Output

### Script

There are two things I want you to clearly distinguish.

First is the **source code**.

This is what the programmer writes.

In our example:

```python
print("Hello, World!")
```

That is our source code.

Second is the **output**.

This is what the program produces after execution.

Our output is:

```text
Hello, World!
```

So:

**Source Code = Instructions written by the programmer**

**Output = Result produced when the program executes**

This distinction will become very important when we start writing larger programs.

If the output is not what we expected, we go back to the source code and investigate what went wrong.

---

# Part 11 — A Small Experiment

### Script

Let's make our first program slightly more interesting.

Change the message to something else.

For example:

```python
print("Welcome to Complete Python Mastery")
```

Run the program again.

Now the output should be:

```text
Welcome to Complete Python Mastery
```

This demonstrates something important.

The `print()` function itself did not change.

We only changed the value we gave to it.

So the same function can be used to display different messages.

Try another example:

```python
print("I am learning Python")
```

Run it.

The output should be:

```text
I am learning Python
```

This is how programming starts to become interactive.

We write instructions, change them, run them, and observe what happens.

Don't be afraid to experiment with small changes.

In fact, experimentation is one of the best ways to learn programming.

---

# Part 12 — Common Beginner Mistakes

### Script

Before we finish, let's discuss a few simple mistakes beginners may encounter.

### Mistake 1 — Forgetting the Parentheses

Incorrect:

```python
print "Hello"
```

At this stage, use the correct Python syntax:

```python
print("Hello")
```

### Mistake 2 — Forgetting the Quotation Marks

For text, we should write:

```python
print("Hello")
```

rather than treating the word as an undefined name.

### Mistake 3 — Incorrect File Extension

Make sure the Python file ends with:

```text
.py
```

For example:

```text
hello.py
```

### Mistake 4 — Running the Wrong File

If you have multiple files open, make sure you are running the Python file that contains the code you want to execute.

### Mistake 5 — Not Saving Changes

If you modify the program, make sure the latest version of your code is saved before running it.

These may seem like small things, but developing good habits from the beginning will make programming much easier later.

---

# Part 13 — What We Have Built Today

### Script

Let's summarize what we have done in this practical session.

We installed **Visual Studio Code**.

We opened VS Code and explored the basic interface.

We installed the **Python extension**.

We created our first Python source file:

```text
hello.py
```

Then we wrote our first Python statement:

```python
print("Hello, World!")
```

We ran the program.

And finally, we saw the output:

```text
Hello, World!
```

So our complete workflow was:

**VS Code → Python Extension → Python File → Write Code → Run → Output**

This is now the basic workflow we will use throughout our Python course.

---

# Part 14 — Your First Python Milestone

### Script

I want you to recognize that today's session is an important milestone.

In the earlier lectures, we talked about programming theoretically.

We discussed what programming means.

We discussed programming languages.

We installed Python.

But today, you actually wrote and executed Python code.

Your first program may contain only one line, but that one line represents the beginning of your programming journey.

From this point forward, our programs will gradually become more powerful.

We will move from displaying simple messages to working with data, variables, operators, conditions, loops, functions, collections, and eventually larger Python projects.

But every programmer starts somewhere.

And this is your starting point.

---

# Part 15 — What's Next?

### Script

Now that our development environment is ready and our first Python program is working, we are ready to start learning the actual building blocks of Python.

In the upcoming lessons, we will move beyond:

```python
print("Hello, World!")
```

and start understanding how Python programs actually work.

We will learn how to store information, work with different types of data, perform operations, make decisions, repeat tasks, and organize our programs.

Each new concept will build on what we have already learned.

So don't worry if today's program looked very simple.

The goal of this lecture was not to build a complicated application.

The goal was to make sure that:

**You can open your development environment, create a Python file, write Python code, execute it, and understand the output.**

That foundation is now ready.

From the next lessons onward, we will start building our Python knowledge step by step.

Thank you for watching.

**See you in the next lecture. Happy Learning, and Happy Coding! 🐍**
