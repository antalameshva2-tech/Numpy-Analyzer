# 🔢 NumPy Analyzer

A beginner-friendly Python project that uses **NumPy** to create and analyze arrays through a menu-driven interface. It demonstrates array creation, indexing, slicing, mathematical operations, combining and splitting arrays, searching, sorting, filtering, and statistical calculations.

## 📌 Project Overview

**NumPy Analyzer** is a command-line application built with Python and NumPy. Users can create 1D, 2D, or 3D arrays and perform different operations on the current array through a simple menu.

## ✨ Features

- **Create NumPy Arrays** — create one-dimensional, two-dimensional, or three-dimensional arrays from user-entered numbers.
- **Indexing and Slicing** — access individual elements and select ranges of array values.
- **Mathematical Operations** — perform addition, subtraction, element-wise multiplication, and division.
- **Combine or Split Arrays** — concatenate arrays and split an array into equal sections when possible.
- **Search, Sort, and Filter** — locate matching values, sort array values, and filter values using a condition.
- **Statistical Operations** — calculate sum, mean, median, standard deviation, and variance.
- **Input Validation** — handle invalid integer input, invalid ranges, and division by zero.
- **Menu-Driven Interface** — choose operations from the displayed menu.

## 🛠️ Technologies Used

- **Python 3.x**
- **NumPy**
- **Git** — version control
- **GitHub** — source-code hosting

## 📂 Project Structure

```text
NumPy-Analyzer/
├── NumPy Analyzer.py
└── README.md
```

## ⚙️ Requirements

- Python 3.x installed on your computer
- NumPy library
- A code editor or terminal, such as VS Code

## 🚀 Installation and Setup

### 1. Clone the repository

Replace `<your-repository-url>` with the URL of your GitHub repository.

```bash
git clone <your-repository-url>
```

### 2. Open the project folder

```bash
cd NumPy-Analyzer
```

### 3. Install NumPy

```bash
python -m pip install numpy
```

### 4. Run the program

```bash
python "NumPy Analyzer.py"
```

> If your Python installation uses `python3` instead of `python`, use `python3` in the commands above.

## 🧭 Main Menu

The program provides these main options:

1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, and Filter Arrays
5. Aggregate and Statistical Functions
6. Exit

The program asks for the required input and runs the selected operation. Some operations require an array to be created first.

## 🧮 Operations Explained

### 1. Create Arrays

Create a 1D, 2D, or 3D NumPy array by entering the required values. For multidimensional arrays, the program uses the provided dimensions to reshape the values into the requested shape.

### 2. Indexing and Slicing

- **Indexing** accesses a particular element using its index.
- **Slicing** selects a range of elements or a section of a multidimensional array.

### 3. Mathematical Operations

The program supports:

- Addition
- Subtraction
- Element-wise multiplication
- Division, with a check to avoid dividing by zero

### 4. Combine or Split Arrays

- **Concatenate:** joins the current array with another array.
- **Split:** divides an array into the requested number of sections when its first axis can be divided evenly.

### 5. Search, Sort, and Filter

- **Search:** finds positions of matching values.
- **Sort:** arranges array values in sorted order.
- **Filter:** selects values that satisfy a Boolean condition.

### 6. Aggregate and Statistical Functions

The program demonstrates these NumPy functions:

| Function | Purpose |
|---|---|
| `np.sum()` | Calculates the sum of array values |
| `np.mean()` | Calculates the arithmetic mean |
| `np.median()` | Finds the median value |
| `np.std()` | Calculates standard deviation |
| `np.var()` | Calculates variance |

## 🧠 Python and NumPy Concepts Practiced

- Classes and objects
- Constructor (`__init__`)
- Class methods (`@classmethod`)
- Static methods (`@staticmethod`)
- Private attributes and helper methods
- NumPy array creation and reshaping
- Array indexing and slicing
- Element-wise arithmetic
- Concatenation and splitting
- Searching, sorting, and Boolean filtering
- Aggregate and statistical functions
- Exception handling and input validation

## ⚠️ Input Validation

The application includes checks for invalid integer input and invalid range formats. It also checks for division by zero and verifies that an array can be split into the requested number of equal sections. Follow the prompts shown in the terminal when entering values.

## 🎯 Learning Objectives

This project is designed to help practise Python class-based programming and common NumPy operations in one interactive application. It is suitable for students and beginners who are learning array manipulation and basic data analytics.

## 🔮 Possible Future Improvements

- Add more NumPy operations, such as broadcasting and reshaping demonstrations.
- Add clearer examples for each operation.
- Add automated tests for array operations and input validation.
- Improve the interface and provide more detailed operation results.

## 👩‍💻 Author

**MESHVA ANTALA**

- GitHub: [antalameshva2-tech](https://github.com/antalameshva2-tech)

## 📄 Version

**v1.0.0**

## 📜 License

This project is intended for educational and learning purposes. Add a license file if you plan to distribute it under a specific open-source license.
