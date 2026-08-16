# Complete Python Mastery — Lecture 3

## Python Installation & Setup — Teaching Script

**Course:** Complete Python Mastery  
**Module:** Module 3 — Building Your Programming Environment  
**Lecture:** 3  
**Topic:** Python Installation & Setup  
**Format:** Detailed Slide-by-Slide Teaching Script  
**Audience:** Complete Beginners

---

# Slide 1 — Building Your Programming Environment

### Script

Good Morning everyone, and welcome back to **Complete Python Mastery**.

In our previous lectures, we focused on understanding the fundamentals behind programming.

First, we learned what programming is, why computers need instructions, and how programmers solve problems.

Then, we learned about programming languages and understood the difference between low-level and high-level languages.

We also learned that **Python is a high-level programming language** and that it is a very beginner-friendly language.

Now we are ready to take an important practical step.

Before we can actually write and execute Python programs on our computer, we need to prepare our programming environment.

And that is exactly what we are going to do in today's lecture.

Today's lesson is about **Python Installation and Setup**.

By the end of this lecture, Python should be installed on our Windows computer, the system should be configured correctly, and we should be able to verify that Python is working from the Command Prompt.

So today, we are moving from **understanding Python** to **preparing the computer to run Python**.

Let's get started.

---

# Slide 2 — The Four Stages of Our Installation Mission

### Script

Before we start clicking through the installation process, let's understand the complete workflow.

There are **four main stages** in our Python installation mission.

### Stage 1 — Download

First, we need to download Python.

But we should not download it from a random website.

We will use the official Python source to obtain the installer.

### Stage 2 — Install

After downloading the installer, we need to install Python on our Windows computer.

This places the required Python files and components on the system.

### Stage 3 — Configure PATH

This is a very important step.

We need to configure the Windows **PATH** so that the operating system can find Python when we use Python commands from Command Prompt.

### Stage 4 — Verify

Finally, we need to confirm that everything is working correctly.

We will open Command Prompt and run a simple command:

```text
python --version
```

If Windows responds with a Python version number, we know that Python has been successfully detected.

So our complete process is:

**Download → Install → Configure PATH → Verify**

Keep these four stages in mind because we will follow them one by one.

---

# Slide 3 — System Requirements for a Local Python Environment

### Script

Before installing Python, let's check whether our computer meets the basic requirements shown in this lecture.

The first requirement is:

**Windows 10 or Windows 11.**

This lecture is specifically focused on setting up Python on Windows.

The second requirement is a:

**Stable internet connection.**

We need internet access to download the Python installer from the official website.

The third requirement is:

**Administrator permissions.**

Depending on the Windows configuration and installation location, administrator permission may be required during setup.

The fourth requirement is:

**Approximately 500 MB of free disk space.**

Python itself does not require a huge amount of storage for a basic installation, but we should make sure that sufficient free space is available.

So before we begin, make sure your system meets these basic requirements.

Once the requirements are satisfied, we can move on to downloading Python.

---

# Slide 4 — Sourcing the Official Python Installer

### Script

Now we are ready for the first practical step:

**Downloading Python.**

The most important rule here is:

**Use the official Python source.**

Open your web browser and go to:

**www.python.org**

This is the official Python website.

Once the website is open, navigate to the **Downloads** section.

From there, select the latest stable version available for Windows.

The important thing is that we want a stable Windows installer from the official source.

Avoid downloading Python from unknown websites or unofficial download pages.

Using the official source helps us obtain the correct and trusted installer.

So the basic process is:

**Open Browser → Visit python.org → Open Downloads → Select the latest stable Windows version**

Once the installer has been downloaded, we can move to the installation stage.

---

# Slide 5 — Executing the Installer and Configuring PATH

### Script

Now we have downloaded the Python installer.

Let's start the installation.

When the installer opens, there is one step that I want you to pay special attention to.

The first step is:

**Check the PATH box.**

This is marked as **Crucial** in the presentation.

Adding Python to PATH makes it possible for Windows to locate Python through Command Prompt.

So before clicking the installation button, make sure the PATH option is selected.

Next:

**Click Install Now.**

The installer will begin copying and configuring the required Python components on your computer.

Now we simply need to wait for the installation process to complete.

Once the installation has finished successfully, click **Close**.

So the practical sequence is:

**Check PATH → Click Install Now → Wait for completion → Click Close**

The PATH step is especially important because we will use it later when verifying Python from Command Prompt.

---

# Slide 6 — How the Operating System Locates Python

### Script

Now let's understand something that happens behind the scenes:

**How does Windows locate Python when we type a Python command?**

Suppose we open Command Prompt and type:

```text
python
```

How does Windows know where Python is installed?

This is where the **PATH** setting becomes important.

Think of PATH as a **map**.

The PATH tells Windows where it can find executable programs.

In our case, the relationship is:

**Command Prompt → Windows PATH → Python Executable File**

When we type a command, Windows checks the locations listed in PATH to find the required executable.

If Python has been correctly added to PATH, Windows can locate the Python executable and run it.

But if Python is not included in PATH, Windows may not know where Python is located.

That is when you may see an error indicating that the `python` command is not recognized.

So remember:

**PATH acts like a map that tells Windows where Python lives.**

This is why checking the PATH option during installation is so important.

---

# Slide 7 — Verifying the Installation via Command Prompt

### Script

Now we have reached the final stage of our basic setup:

**Verification.**

We don't want to assume that Python installed correctly.

We want to test it.

Open **Command Prompt**.

Then type:

```text
python --version
```

And press Enter.

If everything is configured correctly, Command Prompt should display a Python version number.

For example, you may see something similar to:

```text
Python 3.x.x
```

The exact version number can vary depending on the stable version you installed.

The important thing is that Command Prompt successfully recognizes the `python` command and returns a version number.

If you see a Python version number, that means the installation has been successfully detected.

This simple verification step is important because it confirms that Python is not only installed but is also accessible through Command Prompt.

---

# Slide 8 — Diagnostic Matrix for Common Installation Errors

### Script

Now let's talk about what happens if the verification does not work.

Installation problems can happen, especially when setting up a programming environment for the first time.

The lecture covers three common problems.

## Problem 1 — `python` Command Not Recognized

Suppose you type:

```text
python --version
```

but Windows says that the Python command is not recognized.

One possible reason is that Python was not added to PATH.

Another possibility is that Command Prompt was already open before Python was installed and needs to be restarted.

So the first thing to try is:

**Restart Command Prompt.**

If the problem continues, reinstall Python and make sure the PATH option is selected during installation.

---

## Problem 2 — Wrong Version Installed

Another problem is installing an incorrect or outdated Python version.

This can happen if the installer was downloaded from an incorrect source or an older download page.

The solution shown in the lecture is:

**Download the latest stable version directly from python.org.**

This helps ensure that you are using the intended official installer.

---

## Problem 3 — Multiple Python Versions Installed

Another possible issue is having multiple Python versions installed on the same computer.

For example, an older Python installation may already exist while you are installing a newer version.

These installations can sometimes create conflicts.

The solution presented here is to remove older versions through **Windows Settings** and keep the latest required version.

The important lesson is:

**Don't panic when an installation problem occurs.**

First identify the symptom.

Then determine the likely cause.

Finally, apply the appropriate solution.

That is an important part of working with programming environments.

---

# Slide 9 — Your Computer is Now a Python Programming Machine

### Script

Excellent.

If you have followed all the steps successfully, your computer is now ready for Python programming.

Let's quickly review what we have completed.

First, we **downloaded Python securely from the official source**.

Second, we **installed Python successfully on Windows**.

Third, we **configured the system PATH** so Windows can locate Python through Command Prompt.

And finally, we **verified Python functionality** using the Command Prompt.

That means our basic Python environment is ready.

This is an important milestone because, until now, we have mostly been learning the concepts behind programming and programming languages.

Now our computer itself is prepared for practical Python programming.

From this point forward, we can begin writing actual Python code.

---

# Slide 10 — Next Up: Writing Your First Python Program

### Script

Now we are ready for the exciting part.

In the next lesson, we will finally write our **first Python program**.

We will install and set up **Visual Studio Code** along with the **Python Extension**.

Then we will create our very first Python file.

And finally, we will write and run our first Python statement:

```python
print("Hello, World!")
```

This may look like a very small program, but it represents an important milestone.

Until now, we have answered:

**What is programming?**

**What are programming languages?**

**What is Python?**

And today, we prepared our computer to work with Python.

In the next lesson, we will put all of that knowledge into practice.

We will create a Python file, write code inside it, execute the code, and see the output on our screen.

So make sure your Python installation is working correctly before moving forward.

Our Python programming journey officially begins in the next lesson.

Thank you for watching.

**See you in the next lecture. Happy Learning, and Happy Coding! 🐍**
