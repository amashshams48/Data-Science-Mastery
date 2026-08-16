# Complete Python Mastery — Lecture 5

## Variables in Python — Teaching Script

**Course:** Complete Python Mastery  
**Module:** Module 1 — Python Fundamentals  
**Lecture:** 5  
**Topic:** Variables in Python  
**Format:** Detailed Slide-by-Slide Teaching Script  
**Audience:** Complete Beginners

---

# Slide 1 — Lesson 05: Variables in Python

### Script

Good Morning everyone, and welcome back to **Complete Python Mastery**.

In our previous lecture, we wrote and executed our first Python program.

We used the `print()` function to display a message on the screen.

That was a very simple program, but now we are ready to move to one of the most important concepts in programming:

**Variables.**

Think about what happens in a real program.

A program usually needs to work with information.

For example, a student management program may need a student's name, age, marks, and city.

A banking application may need account information.

A shopping application may need product names and prices.

So, we need a way to store and work with information inside our programs.

That is where variables come in.

In today's lecture, we will understand what a variable is, how variables store values, how we create variables in Python, and what rules we need to follow when naming them.

We will also look at valid and invalid variable names.

And at the end, we will open VS Code and create our first variables.

So let's begin.

---

# Slide 2 — What is a Variable?

### Script

Let's start with the definition.

A variable is:

**A named storage location used to store data.**

Now, this definition may sound a little technical at first.

So let's break it down.

The first important word is **named**.

A variable has a name.

The second important idea is **storage**.

We need somewhere to keep information while our program is running.

And the third important idea is **data**.

That data could represent information such as a person's name, age, city, country, or other values.

For example:

```python
name = "Ali"
```

Here, `name` is the variable.

And `"Ali"` is the value stored in that variable.

So we can visualize the relationship as:

**Variable → Stores → Value**

The variable gives us a name through which we can refer to the stored value.

This is one of the most important concepts you need to understand before moving further into Python.

---

# Slide 3 — The Mental Model: A Labeled Container

### Script

Now let's make the idea of a variable even easier to understand.

Imagine that you have a physical box.

You put some information inside that box.

But if you have many boxes, how will you know which box contains what?

You can attach a label to each box.

For example, one box could have the label:

**name**

And inside it, the value could be:

**"Ali"**

This is the mental model shown on this slide.

A variable is like a **labeled container holding a specific piece of information**.

The label is the variable name.

The information inside the container is the value.

So when we write:

```python
name = "Ali"
```

you can mentally imagine:

```text
Label: name
Value: "Ali"
```

This is not saying that Python literally works like a physical box.

It is simply a beginner-friendly mental model that helps us understand the relationship between a variable name and its value.

Later, as we learn more about Python's internal behavior, we can make this model more precise.

But for now, remember:

**A variable gives us a meaningful name through which we can work with a value in our program.**

---

# Slide 4 — Creating Variables: The Anatomy

### Script

Now let's learn how we actually create a variable in Python.

The basic syntax is:

```python
name = "Ali"
```

Let's break this statement into its parts.

First:

```python
name
```

This is the **variable name**.

It is the name we use to refer to the value.

Next we have:

```python
=
```

This is called the **assignment operator**.

In this context, it is used to assign the value on the right to the variable on the left.

And finally:

```python
"Ali"
```

This is the **value**.

So the basic anatomy is:

**Variable Name → Assignment Operator → Value**

Or:

```text
name = "Ali"
```

Now let's look at the other examples on the slide.

```python
age = 20
city = "Delhi"
country = "India"
```

In:

```python
age = 20
```

`age` is the variable name and `20` is the value.

In:

```python
city = "Delhi"
```

`city` is the variable name and `"Delhi"` is the value.

And in:

```python
country = "India"
```

`country` is the variable name and `"India"` is the value.

Notice how we can create multiple variables, each with a meaningful name and its own value.

---

# Slide 5 — Variable Naming Rules

### Script

Now we come to a very important part:

**Variable Naming Rules.**

Python does not allow us to choose absolutely any name we want.

Variable names must follow specific rules.

Let's start with what is allowed.

### First — Letters

Variable names can contain letters.

For example:

```python
name
age
city
```

These are valid.

### Second — Numbers

Numbers can also be used in variable names.

However, there is an important restriction:

**A variable name cannot start with a number.**

For example:

```python
marks2
```

is valid.

But:

```python
2marks
```

is invalid.

### Third — Underscores

We can use the underscore character:

```text
_
```

For example:

```python
student_name
```

or:

```python
_city
```

These are valid according to the rules shown in the lecture.

Now let's look at what is not allowed.

### Spaces

We cannot use spaces inside a variable name.

For example:

```python
my name
```

is invalid.

### Starting with a Number

A variable name cannot begin with a number.

For example:

```python
2name
```

is invalid.

### Python Keywords

We also cannot use Python keywords as ordinary variable names.

For example:

```python
class
```

is a reserved Python keyword.

So the main idea is:

**Choose a valid name that follows Python's naming rules.**

---

# Slide 6 — Valid vs. Invalid Names

### Script

Now let's make the naming rules practical by comparing valid and invalid examples.

On the valid side, we have:

```python
student_name
```

This is valid because it uses letters and an underscore.

Next:

```python
age
```

This is valid.

Next:

```python
marks2
```

This is also valid because the number appears after the beginning of the name.

And:

```python
_city
```

is valid according to Python's naming rules.

Now let's look at the invalid examples.

### Example 1

```python
2name
```

This is invalid because a variable name cannot start with a number.

### Example 2

```python
my name
```

This is invalid because spaces are not allowed in a variable name.

If you want to represent multiple words, you can use an underscore:

```python
my_name
```

### Example 3

```python
class
```

This is invalid because `class` is a reserved Python keyword.

Python uses this word for a specific language feature, so we should not use it as an ordinary variable name.

### Example 4

```python
total-marks
```

This is invalid because the hyphen `-` is not the same thing as an underscore `_`.

If we want to separate words in a variable name, we can write:

```python
total_marks
```

So always pay attention to these small details.

A variable name may look readable to a human, but Python still needs it to follow the language's syntax rules.

---

# Slide 7 — The Core Principles

### Script

Let's bring the main ideas together.

The first principle is:

**Variables store data.**

This is the basic purpose of a variable.

We create variables so that our programs can work with information.

The second principle is:

**Every variable needs a unique name.**

The name gives us a way to refer to that variable in our program.

For example:

```python
name = "Ali"
age = 20
```

Here, `name` and `age` identify two different variables.

The third principle is:

**Names must follow strict Python rules.**

We cannot randomly choose names that contain spaces, start with numbers, or use reserved keywords.

The fourth principle is:

**Variables make programs dynamic and easier to write.**

Instead of writing information repeatedly throughout a program, we can store it in variables and refer to those variables when needed.

For example, if we store:

```python
name = "Ali"
```

we can use `name` wherever we need to work with that information.

This becomes extremely useful as programs become larger.

So variables are not just a small Python feature.

They are one of the fundamental building blocks of programming.

---

# Slide 8 — Let's Start Coding!

### Script

Now it is time to move from theory to practice.

Open **VS Code**.

Create or open your Python file.

Now let's create our first variables.

Start with:

```python
name = "Ali"
```

Here, `name` is the variable name and `"Ali"` is the value.

Now let's create another variable:

```python
age = 20
```

Here, `age` stores the value `20`.

Next:

```python
city = "Delhi"
```

And finally:

```python
country = "India"
```

So our code can look like this:

```python
name = "Ali"
age = 20
city = "Delhi"
country = "India"
```

Now look at what we have done.

We have created four variables:

- `name`
- `age`
- `city`
- `country`

And each variable has a value.

This is the first time we are actually storing information inside variables in Python.

Now let's connect this practical work with the concept we learned earlier.

When we write:

```python
name = "Ali"
```

we are assigning the value `"Ali"` to the variable `name`.

When we write:

```python
age = 20
```

we are assigning `20` to the variable `age`.

The same pattern applies to the other variables.

This is the basic foundation of working with data in Python.

Before we finish, take a moment to experiment.

Try creating another variable with a meaningful name.

For example:

```python
student_name = "Ali"
```

Then check the name carefully.

Does it contain a space?

Does it start with a number?

Does it use an underscore correctly?

This is how you should practice programming: not only by copying code, but by understanding why each line is written and testing small changes yourself.

In the next lessons, we will build on variables and learn more about the different kinds of values we can store and how we can use those values in our programs.

So remember the most important idea from today's lecture:

**Variable = A named way to work with stored data.**

And the basic syntax is:

```python
variable_name = value
```

Thank you for watching.

**See you in the next lecture. Happy Learning, and Happy Coding! 🐍**
