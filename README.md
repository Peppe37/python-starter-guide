# 🐍 Python Starter Guide

A hands-on, example-driven guide to learning Python — from basic concepts to advanced topics and essential libraries.  
This repository is designed for developers who prefer learning by doing, using interactive and well-documented examples.

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
git clone https://github.com/yourusername/python-guide.git
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

Contributions are welcome!  
If you'd like to add examples or improve existing ones:

1. Fork the repo  
2. Create a new branch  
3. Submit a pull request

---

## 📄 License

This project is open-source under the [MIT License](./LICENSE).

