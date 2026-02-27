# 📊 Expectation Decider -- Probability Analysis Project

## 📌 Project Overview

This project analyzes student performance data to understand the
probability factors that influence final exam results.\
The analysis is based on study hours, attendance percentage,
participation in group discussions, and previous test scores.

The goal is to apply core probability concepts such as: - Empirical
Probability - Conditional Probability - Bayes' Theorem - Binomial
Distribution - Contingency Tables - Venn Diagram Representation

------------------------------------------------------------------------

## 📂 Project Structure

    Expectation-Decider/
    │
    ├── expectation_decider_dataset.csv
    ├── _Expectation_Decider_Final_CSV_Updated.ipynb
    ├── Venn_Diagram_Colored_Bordered.png
    └── README.md

------------------------------------------------------------------------

## 🗂 Dataset Description

The dataset contains 200 student records with the following fields:

| Column Name \| Description \|

\|-------------\|-------------\| study_hours \| Number of hours studied
per week \| \| attendance \| Lecture attendance percentage \| \|
group_discussion \| Participation in group discussion (Yes/No) \| \|
previous_test_score \| Internal test marks (out of 100) \| \|
final_exam_pass \| Final exam result (Pass/Fail) \|

------------------------------------------------------------------------

## 📈 Analysis Performed

### 1️⃣ Basic Probability

Calculated probability of passing the exam:

P(Pass) = Number of Students Passed / Total Students

------------------------------------------------------------------------

### 2️⃣ Contingency Table

Analyzed relationship between: - Group Discussion Participation - Final
Exam Result

------------------------------------------------------------------------

### 3️⃣ Conditional Probability

Computed probability of passing given: - Attendance \> 80%

------------------------------------------------------------------------

### 4️⃣ Bayes' Theorem

Applied Bayes formula:

P(Pass \| High Attendance) =\
\[ P(High Attendance \| Pass) × P(Pass) \] / P(High Attendance)

------------------------------------------------------------------------

### 5️⃣ Probability Distribution

Defined random variable:

X = Number of students passing out of 3 randomly selected students.

Used Binomial Distribution:

P(X = k) = nCk × p\^k × (1 − p)\^(n − k)

Also calculated: - Mean = np - Variance = np(1 − p)

------------------------------------------------------------------------

### 6️⃣ Venn Diagram

Visual representation of overlap between: - Study Hours \> 10 -
Attendance \> 80%

See: `Venn_Diagram.png`

------------------------------------------------------------------------


### Option 1: Jupyter Notebook

1.  Install Python

2.  Install dependencies:

        pip install pandas matplotlib seaborn matplotlib-venn

3.  Open notebook:

        jupyter notebook

------------------------------------------------------------------------

## 🧠 Key Insights

-   Higher study hours increase probability of passing.
-   Higher attendance improves exam performance.
-   Combined academic factors significantly raise success probability.
-   Group discussion participation shows positive association with
    results.

------------------------------------------------------------------------

## 📌 Tools Used

-   Python
-   Pandas
-   Matplotlib
-   Seaborn
-   Jupyter Notebook


