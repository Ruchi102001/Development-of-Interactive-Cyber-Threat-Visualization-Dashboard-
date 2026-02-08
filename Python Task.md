# 🔹 What is Python?

**Python** is a **high-level, interpreted, and general-purpose programming language**.  
It is designed to be **easy to read and write**, with a simple syntax similar to English.  

## 🔹 When do we use Python?

- **Web Development** → Building websites & web apps (e.g., Django, Flask)  
- **Data Analysis & Visualization** → Analyzing datasets, creating charts (e.g., Pandas, Matplotlib)  
- **Machine Learning & AI** → Predictive models, AI applications (e.g., Scikit-learn, TensorFlow)  
- **Automation & Scripting** → Automating repetitive tasks, file handling  
- **Game Development** → Simple games (e.g., Pygame)  
- **Networking & Cybersecurity** → Network automation, security tools  

## 🔹 Advantages of Python

1. **Easy to Learn & Read** → Simple syntax, beginner-friendly  
2. **Large Community Support** → Tons of libraries & frameworks  
3. **Cross-platform** → Works on Windows, Mac, Linux  
4. **Versatile** → Can be used in many domains: Web, Data, AI, Automation  
5. **Open Source** → Free to use and distribute

## **Why Python for Data Analysis**

Python is widely used for **Data Analysis** because of its simplicity, readability, and vast ecosystem of libraries. It allows analysts to efficiently **collect, clean, analyze, and visualize data**. Popular libraries like **NumPy, Pandas, Matplotlib, and Seaborn** make Python a preferred choice for data-driven tasks.

---

## **Installing Python & Anaconda**

1. **Python Installation**
   - Go to the [official Python website](https://www.python.org/downloads/).
   - Download the latest version compatible with your OS.
   - Follow the installation instructions and make sure to **check "Add Python to PATH"**.

2. **Anaconda Installation**
   - Anaconda is a **Python distribution** with pre-installed libraries for **Data Science & Machine Learning**.
   - Download from the [official Anaconda website](https://www.anaconda.com/products/distribution).
   - Install it and use **Anaconda Navigator** for managing environments and packages.

---

## **Jupyter Notebook Basics**

Jupyter Notebook is an **interactive coding environment** mainly used for **Python & Data Analysis**.

- **Starting Jupyter Notebook**
  ```bash
  jupyter notebook

## Variables & Data Types

Variables are containers used to store data in a program.
They help in storing, modifying, and retrieving values easily.

## Purpose of Variables

To store data for later use

To make code readable and maintainable

To perform operations on stored data

🔹 Syntax of Variables
variable_name = value


Rules for naming variables:

Must start with a letter or underscore (_)

Can contain letters, numbers, or underscores

Case-sensitive (age and Age are different)

Cannot use Python keywords (if, for, while, etc.)

Example:

name = "Ruchi"
age = 20
salary = 50000.50
is_employed = True

🔹 Data Types in Python

Python automatically identifies the type of data stored in a variable.

1. Numeric Types

int → Integer numbers

age = 25


float → Decimal numbers

salary = 50000.50


complex → Complex numbers

z = 2 + 3j

2. Text Type

str → Strings (text)

name = "Ruchi"

3. Boolean Type

bool → True / False

is_employed = True

4. Type Checking

Use type() function to check the type of a variable:

age = 25
print(type(age))  # Output: <class 'int'>

5. Type Casting

Convert one data type to another:

x = 5      # int
y = float(x)  # float
z = str(x)    # str
