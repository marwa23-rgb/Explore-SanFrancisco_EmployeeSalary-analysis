<h1 align="center">💼 San Francisco Employee Salary Analysis</h1>

<p align="center">
  Exploratory data analysis of San Francisco city employee salaries and benefits using Python
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
  <a href="https://www.kaggle.com/"><img src="https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle"></a>
</p>

## 📌 Overview

This project explores the **San Francisco City Salary** dataset, a public dataset with salary and benefits data for San Francisco city employees. It cleans the data and answers 18 questions with Pandas to understand the factors that influence pay, such as job title and year, and to spot patterns that could support salary equity decisions.

---

## ⚡ At a Glance

| ❓ Questions Answered | 🧹 Columns Dropped | 🛠️ Main Tool |
|:---:|:---:|:---:|
| **18** | **5** | **Pandas** |

---

## 🔄 Workflow

1. **Load & Inspect** – Reviewed the structure and contents of the data (`head()`, `info()`, `describe()`, shape).
2. **Clean** – Dropped the `Id`, `Notes`, `Agency`, `Status` and `Benefits` columns, replaced `Not Provided` in `EmployeeName` with `NaN`, and dropped rows with 5 missing values.
3. **Analyze** – Used filtering, `value_counts()`, `groupby()` and string operations to answer 18 questions.

---

## 🔍 Questions Answered

**Dataset & cleaning**

| # | Question |
|:---:|---|
| 1 | What is the shape of the dataset (rows and columns)? |
| 2 | Are there null values in the dataset? |
| 3 | Which columns can be dropped (ID, Notes, Agency, Status, Benefits)? |
| 4 | What are the overall statistics of the dataframe? |
| 5 | How can `Not Provided` in `EmployeeName` be replaced with `NaN`? |
| 6 | How can rows with 5 missing values be dropped? |

**Exploration**

| # | Question |
|:---:|---|
| 7 | Which employee names occur most often (top 5)? |
| 8 | How many unique job titles are there? |
| 9 | How many job titles contain "Captain"? |
| 10 | Which employees work in the Fire Department? |
| 11 | What are the top 5 most common jobs? |

**Salary analysis**

| # | Question |
|:---:|---|
| 12 | What are the minimum, maximum and average `BasePay`? |
| 13 | Who has the highest `BasePay`? |
| 14 | What is the job title of ALBERT PARDINI? |
| 15 | How much does ALBERT PARDINI make (including benefits)? |
| 16 | What is the average `BasePay` of all employees per year? |
| 17 | What is the average `BasePay` per job title? |
| 18 | What is the average `BasePay` for the job title ACCOUNTANT? |

## 👩‍💻 Author

**Marwa Samy** · [GitHub](https://github.com/marwa23-rgb)
