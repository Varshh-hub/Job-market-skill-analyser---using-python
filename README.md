# 📊 Job Market Skill Analyzer

A Python project developed as part of **Week 1** of the **Advanced Data Science Program** using **Google Colab**.

This project analyzes job postings, cleans skill data, identifies the most frequently requested skills, and exports the processed data into structured files.

---

## 🚀 Project Overview

The **Job Market Skill Analyzer** is a beginner-friendly Python application that demonstrates the use of Python Data Structures and core programming concepts to process and analyze job market data.

The project starts with a predefined dataset of job postings and allows users to add new postings, clean skill information, analyze skill frequency, search for jobs by skill, and save the cleaned data for future use.

---

## 💻 Platform

- Google Colab
- Python 3

---

## 📂 Dataset

Each job posting contains:

- Job ID
- Job Role
- Company Name
- Required Skills

Example:

| Job ID | Role | Company | Skills |
|--------|------|---------|--------|
| 1 | Data Analyst | Google | Excel SQL Python Tableau |
| 2 | Data Scientist | Microsoft | Python Machine Learning Statistics |

---

## ✨ Features

### 📌 Display Job Postings
Displays all job records in a structured format.

### ➕ Add New Job Postings
- Accepts user input
- Automatically generates the next Job ID
- Updates the dataset dynamically

### 🧹 Clean & Normalize Skills
The `clean_skills()` function:
- Converts text to lowercase
- Replaces commas, periods, and slashes with spaces
- Removes extra whitespace

### 📈 Skill Frequency Analysis
- Extracts every skill from the dataset
- Counts occurrences of each skill
- Displays the Top 5 most requested skills

### 📊 Job Statistics
Displays:
- Total number of job postings
- Number of unique skills
- Roles that require Python

### 🔍 Search Jobs by Skill
The `find_jobs_by_skill()` function allows users to search for jobs based on a specific skill and returns:
- Job ID
- Role
- Company

### ⚡ Lambda & Filter
Uses a **lambda function** with `filter()` to identify job roles containing commonly requested skills.

### 📝 Unique Skills
Displays all unique skills in alphabetical order.

### 💾 File Export
Creates:

- `job_skills.csv` – Contains cleaned job records
- `top_skills.txt` – Stores the most requested skills

Uses **try-except-else-finally** for safe file handling.

---

## 🛠 Python Concepts Used

- Variables
- Lists
- Dictionaries
- Loops
- Functions
- User Input
- Conditional Statements
- String Manipulation
- Lambda Functions
- Filter
- List Comprehensions
- Sets
- File Handling
- Exception Handling

---

## 📁 Project Structure

```
Job-Market-Skill-Analyzer/
│
├── Assignment01.ipynb
├── job_skills.csv
├── top_skills.txt
└── README.md
```

---

## 📚 Learning Outcomes

This project helped me strengthen my understanding of:

- Python Data Structures
- Data Cleaning Techniques
- Text Processing
- Frequency Analysis
- Search Functions
- Functional Programming using Lambda
- CSV File Handling
- Exception Handling
- Writing modular Python code

---

## 🔮 Future Improvements

- Analyze larger datasets using Pandas
- Add data visualizations using Matplotlib and Seaborn
- Store records in an SQL database
- Build an interactive Streamlit dashboard
- Perform advanced job market trend analysis

---

## 📖 Assignment Details

**Program:** Advanced Data Science Program

**Week:** 1

**Assignment:** Python Data Structures

**Project:** Job Market Skill Analyzer

**Platform:** Google Colab

---

## 👩‍💻 Author

**Varsha A**

B.Sc. Artificial Intelligence & Machine Learning Graduate

Aspiring Data Scientist | Python Developer | SQL | Power BI | Machine Learning

---

⭐ If you found this project helpful, consider giving it a star!
