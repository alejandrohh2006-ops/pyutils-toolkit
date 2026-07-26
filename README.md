# pyutils-toolkit

A collection of small, reusable Python utility functions for everyday tasks.

## 📌 What is this?

`pyutils-toolkit` is a lightweight set of helper functions for common tasks that come up again and again in everyday Python projects — string handling, date formatting, simple validation, and JSON I/O — without needing a heavy external dependency.

## ✨ Features

- **String utilities**: clean and format text easily
- **Date helpers**: format and parse dates without boilerplate
- **Validation**: quick checks for emails and other common formats
- **JSON helpers**: simplified reading/writing of JSON files

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/alejandrohh2006-ops/pyutils-toolkit.git
cd pyutils-toolkit
```

## 🔧 Usage

```python
from utils import is_valid_email, format_date, slugify

is_valid_email("test@example.com")  # True
format_date("2026-07-26")           # "July 26, 2026"
slugify("Hello World!")             # "hello-world"
```

## 📂 Project structure
