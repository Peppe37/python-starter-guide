# 🐍 Python Starter Guide

A hands-on, example-driven guide to learning Python — from basic concepts to advanced topics and essential libraries.  
This repository is designed for developers who prefer learning by doing, using interactive and well-documented examples.

## Index
[[__TOC__]]

---

## Prerequisites
- Basic understanding of programming concepts
- Basic knowledge of command line operations
- Basic understanding of Git
- Basic understanding of Python (helpful but not mandatory)
- **Inprescindible: hunger to learn!**

---

## 📁 Repository Structure

```
python-guide/
│
├── examples/
│   ├── basic/          # Fundamental Python concepts (syntax, data types, control flow, etc.)
│   ├── advanced/       # Advanced topics (OOP, decorators, generators, async, etc.)
│   └── libs/           # Popular libraries (NumPy, Pandas, Matplotlib, etc.)
│
├── environment.yml      # Conda environment file
└── README.md            # This file
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Peppe37/python-starter-guide
cd python-guide
```

---

### 2. Set up the Conda environment

Make sure you have [Anaconda](https://www.anaconda.com/download) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.

Create the environment:

```bash
conda env create -f environment.yml
```

Activate it:

```bash
conda activate python-guide
```

---

### 3. Recommended VS Code setup

We recommend using [Visual Studio Code](https://code.visualstudio.com/) with the following extensions for the best experience:

| Extension | Description |
|------------|--------------|
| **Python** (by Microsoft) | Core Python support (linting, debugging, notebooks) |
| **Jupyter** | Run and edit `.ipynb` notebooks directly in VS Code |
| **Pylance** | Fast and feature-rich IntelliSense |
| **Black Formatter** | Consistent Python code formatting |
| **isort** | Automatically organize imports |
| **GitLens** | Enhanced Git integration |
| **Markdown All in One** | Better Markdown editing experience |

#### Optional setup

Enable auto-formatting on save:
1. Open **Settings → Text Editor → Formatting**  
2. Enable **"Format on Save"**  
3. Choose **Black** as the default Python formatter.

---

### 4. Run examples

You can execute any script directly:

```bash
python examples/basic/hello_world.py
```

Or launch Jupyter notebooks (if provided):

```bash
jupyter notebook
```

---

## 🧠 Topics Covered

- **Basic Python syntax**
- **Data structures** (lists, tuples, sets, dicts)
- **Functions & modules**
- **File handling**
- **Error handling**
- **Object-Oriented Programming**
- **Decorators and generators**
- **Asynchronous programming**
- **NumPy, Pandas, Matplotlib, and more**

---

## 💡 Contributing

### Contributions are welcome!  
If you want to contribute:
- Please make sure to follow the existing code style and documentation format.
- Make sure to test your changes before submitting a pull request.
- Use convenient commit messages.

Follow this easy process:
1. Fork the repo  
2. Create a new branch  
3. Submit a pull request

---

## 📄 License

This project is open-source under the [MIT License](./LICENSE).

---

# Happy coding! 🐍🚀