# 📊 Interactive Personal Data Collector

**Author:** Siddhi Patel  
**Course/Project:** Python Practical Assignment

A Python-based console application designed to collect user input, handle different data types (`str`, `int`, `float`), inspect object metadata using `type()` and `id()`, and perform a basic arithmetic calculation.

## 🎯 Project Objectives

- 👤 **User Input Handling:** Collect personal information dynamically using `input()`.

- 🔍 **Data Type Inspection:** Display the data type and memory address of variables using `type()` and `id()`.

- 🧮 **Basic Calculation:** Calculate the user's approximate birth year based on their age.

## ✨ Features & Functionality

### 1. 📝 Data Collection

The program collects:

- Name as a string
- Age as an integer
- Height as a floating-point number
- Favorite number as an integer

### 2. 🔬 Data Type & Memory Inspection

The program displays each entered value along with:

- Its Python data type using `type()`
- Its object identity using `id()`

### 3. 📅 Age-to-Year Calculator

The program calculates the approximate birth year using:

```python
birth_year = 2026 - age
```

## 💻 Technologies Used

- Python 3
- Visual Studio Code
- Git & GitHub

## 📚 Concepts Covered

- `input()`
- Variables
- `str`, `int`, `float`
- Type conversion
- Built-in functions
- `type()`
- `id()`
- Arithmetic operations
- Console output

## 📂 Project Files

```text
Project-1/
│
├── Fundamental_Booster.py
├── README.md
└── output.png
```

## 🖥️ Sample Output

```text
welcome to the intrective personal data collecter

please enter your name: Jenisha Ramani
please enter your age: 20
please enter your height in meters: 130
please enter your favorite number: 5

thank you for providing your information!

name:  Jenisha Ramani (type:  <class 'str'> , memory address:  1411344416240 )
age:  20 (type:  <class 'int'> , memory address:  140711764674264 )
height:  130.0 (type:  <class 'float'> , memory address:  1411341333392 )
favorite number:  5 (type:  <class 'int'> , memory address:  140711764673784 )

Your birth year is approximately: 2006 (based on your age of 20 )

Thank you for using the Personal Data Collector. Goodbye!
```
