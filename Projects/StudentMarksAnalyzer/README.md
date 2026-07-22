# Student Marks Analyzer

## Overview

Student Marks Analyzer is a Python-based data analysis project that simulates the result processing system of a school or college. The project automatically generates student records, calculates academic performance metrics, performs subject-wise analysis, identifies toppers, and generates professional reports in CSV and Word formats.

This project was built using Python, NumPy, Pandas, and python-docx to strengthen practical data analysis skills through a real-world application.

---

## Project Objectives

* Generate and manage student academic data.
* Analyze student performance automatically.
* Calculate grades, percentages, and pass/fail status.
* Identify toppers and rank high-performing students.
* Perform subject-wise performance analysis.
* Generate reports for administrators and teachers.
* Export analytical results to CSV and Word documents.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Faker
* python-docx

---

## Dataset Generation

The project automatically generates:

* 500 student records
* Unique roll numbers
* Random marks for six subjects
* Alphabetically sorted student names

### Subjects Included

* Mathematics
* Science
* Social Science
* English
* Marathi
* Kannada

---

## Features

### Student Record Generation

* Generates 500 student records automatically.
* Creates unique roll numbers.
* Generates realistic student names using Faker.
* Creates subject marks using NumPy.

### Academic Calculations

* Total Marks Calculation
* Percentage Calculation
* Grade Calculation

### Pass/Fail Analysis

A student is considered:

* Pass → Marks ≥ 35 in all subjects
* Fail → Marks < 35 in one or more subjects

The system also records the exact subjects in which a student has failed.

Example:

| Student | Result | Failed Subjects |
| ------- | ------ | --------------- |
| Rahul   | Fail   | Maths, Science  |
| Priya   | Pass   | None            |

---

## Grading System

| Percentage     | Grade |
| -------------- | ----- |
| 90 and above   | A+    |
| 80 - 89        | A     |
| 70 - 79        | B+    |
| 60 - 69        | B     |
| 50 - 59        | C+    |
| Below 50       | C     |
| Failed Student | F     |

---

## Topper Analysis

The system:

* Considers only passed students.
* Sorts students based on total marks.
* Identifies the Top 10 Toppers.
* Determines the Overall Topper.

### Topper Information Includes

* Roll Number
* Name
* Total Marks
* Percentage
* Grade

---

## Subject-Wise Analysis

For every subject, the project calculates:

* Subject Topper
* Topper Marks
* Number of Passed Students
* Number of Failed Students
* Pass Percentage
* Fail Percentage
* Average Marks
* Subject Performance Status

### Subject Status Rules

| Pass Percentage | Status  |
| --------------- | ------- |
| 85% and above   | Good    |
| 70% - 84%       | Average |
| Below 70%       | Poor    |

---

## Key Insights Generated

The system automatically identifies:

* Easiest Subject
* Most Difficult Subject
* Overall Pass Percentage
* Overall Fail Percentage
* Overall Topper

---

## Reports Generated

### CSV Reports

* Class_Report.csv
* Passed_students.csv
* Failed_students.csv
* Top_10_list.csv
* Subject_wise_Analysis.csv

### Word Report

* Student_Performance_Report.docx

The report contains:

* Overall Statistics
* Overall Topper Details
* Top 10 Toppers
* Subject-wise Analysis
* Key Insights

---

## Project Workflow

```text
Generate Student Data
        ↓
Create DataFrame
        ↓
Calculate Total Marks
        ↓
Calculate Percentage
        ↓
Determine Pass / Fail
        ↓
Assign Grades
        ↓
Find Top 10 Toppers
        ↓
Perform Subject Analysis
        ↓
Generate CSV Reports
        ↓
Generate Word Report
```

---

## Sample Output

### Overall Statistics

```text
Total Students : 500
Passed Students : 421
Failed Students : 79

Pass Percentage : 84.20%
Fail Percentage : 15.80%
```

### Overall Topper

```text
Name : Christopher
Total Marks : 528
Percentage : 88.00%
Grade : A
```

---

## Learning Outcomes

Through this project, I learned:

* Data Generation using Faker
* NumPy Array Operations
* Pandas Data Analysis
* Data Cleaning and Transformation
* Function-Based Programming
* Report Automation
* CSV File Handling
* Word Document Generation
* Project Structuring

---

## Future Improvements

Planned enhancements:

* Student Ranking System
* Interactive Dashboard
* Data Visualization using Matplotlib
* Subject Performance Charts
* PDF Report Generation
* GUI Application using Tkinter
* Database Integration
* Web-Based Dashboard

---

## Author

**Nikhil Kanbarkar**

Bachelor of Engineering (Electronics and Communication Engineering)

Aspiring AI/ML Engineer

GitHub: nikhilkanbarkar

## 📄 License

This project is open source and available for personal and educational use.

---

⭐ If you found this project useful, consider giving it a star on GitHub!