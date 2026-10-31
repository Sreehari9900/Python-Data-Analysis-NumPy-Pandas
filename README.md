<p align="center">
  
  ## Data Analysis using NumPy and Pandas 
  
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NumPy-Array%20Operations-013243?logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-Series%20%26%20DataFrame-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" alt="Status">
</p>

---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)
2. [Contents of the Project](#-contents-of-the-project)
3. [Problem Statement](#-problem-statement)
4. [Objectives](#-objectives)
5. [Tech Stack & Tools](#-tech-stack--tools)
6. [Repository Structure](#-repository-structure)
7. [Code Output](#-code-output)
8. [How to Run](#-how-to-run)
9. [Final Conclusion](#-final-conclusion)
10. [Outcomes](#-outcomes)
11. [About the Author](#-about-the-author)

---

<img src="images/sec_overview.png" alt="Project Overview" width="100%">

## 📌 Project Overview

**Python DA Assignment 1** is a hands-on data analysis project that demonstrates the core skills of two of the most important Python libraries for data work: **NumPy** and **Pandas**.

Using three small, realistic datasets, the project covers:

- **Numerical computing** with NumPy arrays (daily temperature readings)
- **One-dimensional labelled data** with Pandas Series (student marks)
- **Tabular data analysis** with Pandas DataFrames (sales transactions)

Every task is solved in a single, well-commented Python script, and its real console output is captured in this repository.

<p align="center">
  <img src="images/workflow.png" alt="Project workflow" width="90%">
</p>

---

<img src="images/sec_contents.png" alt="Contents of the Project" width="100%">

## 📚 Contents of the Project

| Part | Topic | Dataset | Key Skills Covered |
|:----:|-------|---------|--------------------|
| **1** | **NumPy Array Operations** | Daily average temperatures (2 weeks, °C) | 1D & 2D arrays, shape / dtype / size, Celsius → Fahrenheit, `max` / `min` / `mean`, slicing & indexing |
| **2** | **Pandas Series** | Marks of 5 ranked students | Custom index, `iloc` / `loc`, boolean masking, modifying, `drop`, arithmetic on a Series |
| **3** | **Pandas DataFrame** | 10 sales transactions | `head` / `tail` / `shape` / `dtypes`, column selection, filtering, `value_counts`, `unique`, `groupby`, add / update / delete rows and columns |

---

<img src="images/sec_problem.png" alt="Problem Statement" width="100%">

## ❓ Problem Statement

> **Can we turn raw numbers into useful answers using only NumPy and Pandas?**

Raw data is only useful when it can be stored, explored and changed quickly and correctly. This project tackles that challenge through three small real-world situations:

| 🌡️ Situation 1: Weather | 🎓 Situation 2: Exam results | 🛒 Situation 3: Sales records |
|---|---|---|
| Two weeks of daily temperatures (°C) must be stored, converted to Fahrenheit, summarised (max, min, mean) and sliced by day. | Five ranked students' marks must be looked up by label and position, filtered (marks > 90), corrected and converted to CGPA. | Ten transactions must be explored, filtered (North region and Amount > 200), grouped by region, and edited (update, add, remove). |
| **Tool: NumPy** | **Tool: Pandas Series** | **Tool: Pandas DataFrame** |

The goal is to solve all three situations with clean, readable Python code and to verify each result against the expected output.

📄 Original assignment: [`Python_DA_Assignment_1.pdf`](Python_DA_Assignment_1.pdf)

---

<img src="images/sec_objectives.png" alt="Objectives" width="100%">

## 🎯 Objectives

1. ✅ Create and inspect **NumPy arrays** (1D and 2D) and apply vectorised calculations
2. ✅ Use **slicing and indexing** to extract the exact data needed
3. ✅ Build a **Pandas Series** and access it with `loc`, `iloc` and boolean masks
4. ✅ Explore a **DataFrame** with filtering, `value_counts`, `unique` and `groupby`
5. ✅ **Add, update and remove** data in Series and DataFrames safely

---

<img src="images/sec_tech.png" alt="Tech Stack" width="100%">

## 🛠️ Tech Stack & Tools

| Tool | Purpose |
|------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | Programming language |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) | Numerical arrays and computations |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Series and DataFrame analysis |
| ![Git](https://img.shields.io/badge/Git%20%26%20GitHub-181717?logo=github&logoColor=white) | Version control and hosting |

---

<img src="images/sec_structure.png" alt="Repository Structure" width="100%">

## 🗂️ Repository Structure

```text
Python-DA-Assignment-1/
│
├── README.md                        # Project documentation
├── Python_DA_Assignment_1.py        # Complete solution code (all 3 parts)
├── Python_DA_Assignment_1.pdf       # Original assignment problem statement
├── outputs/
│   └── full_output.txt              # Captured console output
└── images/                          # Banners, charts and output screenshots
```

---

<img src="images/sec_output.png" alt="Code Output" width="100%">

## 💻 Code Output

Five key results from running `Python_DA_Assignment_1.py` (full output in `outputs/full_output.txt`):

**1️⃣ NumPy 1D array: properties, Fahrenheit, max / min / mean, slicing**

<img src="images/output_numpy_a.png" alt="NumPy 1D output" width="85%">

**2️⃣ NumPy 2D array: shape, size and weekend slicing**

<img src="images/output_numpy_b.png" alt="NumPy 2D output" width="85%">

**3️⃣ Pandas Series: indexing, masking, edit and CGPA**

<img src="images/output_series.png" alt="Pandas Series output" width="85%">

**4️⃣ DataFrame: filtering, value counts and groupby**

<img src="images/output_df_b.png" alt="DataFrame filtering and groupby" width="85%">

**5️⃣ DataFrame: update, add, remove and delete**

<img src="images/output_df_c.png" alt="DataFrame manipulation" width="85%">

---

<img src="images/sec_run.png" alt="How to Run" width="100%">

## 🚀 How to Run

1. **Clone** the repo: `git clone https://github.com/<your-username>/Python-DA-Assignment-1.git`
2. **Open** the folder: `cd Python-DA-Assignment-1`
3. **Install** the libraries: `pip install numpy pandas`
4. **Run** the script: `python Python_DA_Assignment_1.py`
5. **Check** the results in the terminal (or paste the code into Jupyter / Google Colab)

---

<img src="images/sec_conclusion.png" alt="Final Conclusion" width="100%">

## 🏁 Final Conclusion

1. **NumPy** makes numerical work fast: Week 1 averaged **23.54 °C** (high 26.1 °C, low 20.8 °C).
2. **Pandas Series** adds labels to 1D data, so values can be found by name or position.
3. **Pandas DataFrame** answers business questions: **East** had the highest average sale (**375**).
4. **Electronics** was the most frequent category (**4 of 10** transactions).
5. Together, NumPy and Pandas turn raw data into clear answers in just a few lines of code.

---

<img src="images/sec_outcomes.png" alt="Outcomes" width="100%">

## 🌟 Outcomes

1. ✔️ Confident creation and inspection of NumPy arrays
2. ✔️ Skill in `loc`, `iloc`, slicing and boolean masking
3. ✔️ Practical filtering, grouping and aggregation of DataFrames
4. ✔️ Safe modification of data (update, add, drop) in Pandas
5. ✔️ A clean, documented repository ready to share

---

<img src="images/sec_author.png" alt="About the Author" width="100%">

## 👤 About the Author

**Yallappagari Srihari**

- 🎓 **B.Pharm**, JNTU Kakinada (Chaitanya College of Pharmacy), 2020 to 2024
- 💼 **Safety Associate (Medical Device Complaint Handling)** at 4C Drug Safety Services, Jul 2024 to May 2026
- 🧰 Tools: TrackWise, SAP, Salesforce, Python (NumPy, Pandas)
- 📍 Sathya Sai district, Andhra Pradesh, India

**Connect with me**

[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/<your-username>)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/<your-profile>)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:<your-email>)

---

<p align="center">⭐ If you found this project useful, please give it a star! ⭐</p>
