# Student Marks Analysis (Core Python)

## Overview

The **Student Marks Analysis** project is a simple Python-based application that reads student marks from a CSV file, calculates average marks, determines pass/fail status, and generates a report.

This project is useful for beginners who want to learn:

* CSV file handling in Python
* Functions and modular programming
* Lists and dictionaries
* Data processing and report generation
* Basic student performance analysis

---

# Features

* Read student data from a CSV file
* Calculate average marks of students
* Classify students as Pass or Fail
* Generate a summarized report
* Save processed results into a new CSV file
* Beginner-friendly Python project

---

# Technologies Used

* Python 3
* CSV Module
* Jupyter Notebook

---

# Project Structure

```bash
Student-Marks-Analysis/
│
├── Student Marks Analysisi project Code.ipynb
├── students.csv
├── report.csv
└── README.md
```

---

# Sample Dataset

The project uses a CSV file containing student marks.

## Example: `students.csv`

```csv
Name,Math,Science,English
Shrirang,85,78,92
Amit,65,70,58
Priya,90,88,95
Ravi,45,50,40
Sneha,72,68,80
```

---

# How the Project Works

1. Read student data from the CSV file.
2. Store records using dictionaries and lists.
3. Calculate average marks.
4. Determine pass/fail status.
5. Generate and save the final report.

---

# Main Functions

## Read Data

Reads student records from the CSV file.

```python
def read_data(filename):
```

## Calculate Average

Calculates the average marks of a student.

```python
def calculate_average(student):
```

## Generate Report

Creates a report with average marks and status.

```python
def generate_report(students):
```

## Save Report

Saves the generated report into a CSV file.

```python
def save_report(report, filename):
```

---

# Output Example

## Generated Report

```csv
Name,Average,Status
Shrirang,85.0,Pass
Amit,64.33,Pass
Priya,91.0,Pass
Ravi,45.0,Fail
Sneha,73.33,Pass
```

---

# Learning Outcomes

By completing this project, you will learn:

* File handling using CSV files
* Working with Python dictionaries and lists
* Function-based programming
* Data processing techniques
* Simple report generation

---

# Future Improvements

* Add graphical visualizations using Matplotlib
* Create a GUI using Tkinter
* Store data in a database
* Add subject-wise topper analysis
* Export reports in Excel format

---

# How to Run the Project

## Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/student-marks-analysis.git
```

## Step 2: Open the Project Folder

```bash
cd student-marks-analysis
```

## Step 3: Run the Notebook

Open the Jupyter Notebook and execute all cells.

```bash
jupyter notebook
```

---

# Author

Developed by Soham Darne

---

# License

This project is for educational purposes only.
