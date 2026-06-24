# Anime Rating Prediction Project

This repository contains two Jupyter notebooks:

* **`exploratory_data_analysis.ipynb`** – Exploratory Data Analysis (EDA) and data visualization.
* **`models_evalml_pycaret.ipynb`** – Model training and evaluation using EvalML and PyCaret.

## Requirements

* Python 3.10.9
* pip
* Jupyter Notebook
* Visual Studio Code (recommended)

Dependencies are listed in `requirements.txt`.

---

# Environment Setup

## Option 1: Windows 11 + Visual Studio Code (Tested Environment)

This project was developed and tested on:

* Windows 11
* Visual Studio Code
* Python 3.10.9

### 1. Install Python 3.10.9

Download Python 3.10.9 from:

https://www.python.org/downloads/release/python-3109/

During installation, check:

* ✅ Add Python to PATH

Verify:

```bash
python --version
```

Expected:

```text
Python 3.10.9
```

---

### 2. Clone the Repository

```bash
git clone <repository_url>
cd <repository_name>
```

---

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

**Command Prompt**

```cmd
.venv\Scripts\activate
```

**PowerShell**

```powershell
.venv\Scripts\Activate.ps1
```

---

### 4. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

### 5. Open with Visual Studio Code

```bash
code .
```

Install the following extensions:

* Python
* Jupyter

---

### 6. Select the Python Interpreter

In VS Code:

1. Press **Ctrl+Shift+P**
2. Search:

```
Python: Select Interpreter
```

3. Select:

```
.venv\Scripts\python.exe
```

---

### 7. Run the Notebooks

Open:

* `exploratory_data_analysis.ipynb`
* `models_evalml_pycaret.ipynb`

For each notebook:

1. Click **Select Kernel**
2. Choose the `.venv` interpreter.
3. Run all cells:

```
Run → Run All
```

---

# Option 2: Linux or macOS (using pyenv)

## 1. Install pyenv

### macOS

```bash
brew install pyenv
```

### Ubuntu

```bash
curl https://pyenv.run | bash
```

Add pyenv to your shell configuration:

```bash
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"
```

Reload your shell:

```bash
source ~/.bashrc
```

or

```bash
source ~/.zshrc
```

---

## 2. Install Python 3.10.9

```bash
pyenv install 3.10.9
```

Set the local Python version:

```bash
pyenv local 3.10.9
```

Verify:

```bash
python --version
```

Expected:

```text
Python 3.10.9
```

---

## 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

### Linux

```bash
source .venv/bin/activate
```

### macOS

```bash
source .venv/bin/activate
```

---

## 4. Install Dependencies

Upgrade pip:

```bash
pip install --upgrade pip
```

Install required packages:

```bash
pip install -r requirements.txt
```

---

## 5. Install Jupyter

```bash
pip install notebook
```

---

## 6. Run the Notebooks

Start Jupyter:

```bash
jupyter notebook
```

Then open and execute:

* `exploratory_data_analysis.ipynb`
* `models_evalml_pycaret.ipynb`

Run all cells in each notebook.

---

# Project Structure

```text
.
├── exploratory_data_analysis.ipynb
├── models_evalml_pycaret.ipynb
├── requirements.txt
└── README.md
```

---

# Notes

* The project requires **Python 3.10.9**.
* Using a virtual environment is highly recommended.
* The primary development and testing environment was **Windows 11 with Visual Studio Code**.
* Linux and macOS are also supported using **pyenv**.
