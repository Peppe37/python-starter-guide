# 🐍 Python Start Guide

Welcome to the **Python Start Guide**! This guide will walk you through Python fundamentals with examples you can run interactively.  
Whether you are a complete beginner or coming from another language, this guide will help you get started quickly.

---

## Index
- [🐍 Python Start Guide](#-python-start-guide)
  - [Index](#index)
  - [What is Python?](#what-is-python)
  - [Python Installation](#python-installation)
    - [Windows / macOS / Linux](#windows--macos--linux)
  - [Installing Packages with pip](#installing-packages-with-pip)
  - [Python Syntax](#python-syntax)
  - [Variables](#variables)

---

## What is Python?

Python is a **high-level, interpreted programming language** created by Guido van Rossum in 1991.  
It is designed to be **easy to read and write**, emphasizing **simplicity and readability**.  

Key features:

- Interpreted — no compilation needed
- Dynamically typed — you don’t need to declare variable types
- Cross-platform — runs on Windows, Linux, macOS, and more
- Open-source — free to use and distribute
- Large ecosystem — thousands of libraries and frameworks

Python is widely used in:

- Web development
- Data science and machine learning
- Automation and scripting
- Game development
- Scientific computing

---

## Python Installation

### Windows / macOS / Linux

1. Download **Miniconda / Anaconda** (recommended for beginners) or the official Python installer:  
   [Python Official Website](https://www.python.org/downloads/)

2. Install following instructions for your OS. For Windows, you can also use **WSL + Miniconda** for a more Linux-like environment.

3. Verify the installation:

```bash
python --version
```

or

```bash
python3 --version
```

---

## Installing Packages with pip

Python comes with **pip**, a package manager that lets you install external libraries.  

Example:

```bash
pip install requests
```

Check installed packages:

```bash
pip list
```

> Tip: If using Conda, you can also use `conda install <package>` for many common packages.

---

## Python Syntax

Python emphasizes **readability**.  

- Indentation is **mandatory** (no braces `{}` like C/Java)
- Code blocks are defined by **tabs**
- Comments start with `#`

Example:

```python
# This is a comment
print("Hello, Python!")  # Prints a message
```

---


## Variables

In Python, variables are used to **store data**.  
You don’t need to declare their type explicitly, Python infers it automatically.

Examples:

```python
# Numbers
x = 10          # integer
y = 3.14        # float

# Text
name = "Alice"  # string

# Boolean
is_active = True

print(x, y, name, is_active)
```

Variables can be **reassigned** at any time:

```python
x = 5
print(x)  # Output: 5

x = "Hello"
print(x)  # Output: Hello
```

---
