# Statistical Data Analysis Using Python

## 📌 Project Overview

This project performs statistical data analysis on the **Student Performance in Exams** dataset using Python. The project covers data cleaning, descriptive statistics, statistical testing, correlation analysis, and data visualization.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* ReportLab
* Jupyter Notebook

## 📊 Dataset

The dataset contains student performance information including:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

The dataset contains **1,000 student records** and **8 original columns**.

## 🔍 Analysis Performed

### Data Cleaning

* Checked missing values
* Checked duplicate records
* Verified data types
* Converted score columns to numeric format
* Created an overall student score

### Statistical Analysis

* Mean
* Median
* Standard deviation
* Minimum and maximum
* Skewness
* Kurtosis
* Correlation analysis
* Pearson correlation test
* Independent t-test
* One-way ANOVA

### Data Visualization

The project generates and saves charts for:

* Math score distribution
* Reading score distribution
* Writing score distribution
* Average scores by gender
* Test preparation performance
* Score correlation heatmap
* Student score box plot
* Parental education analysis
* Lunch type analysis
* Gender distribution
* Test preparation distribution
* Overall score distribution
* Subject-wise average scores

All charts are saved inside the:

```text
notebook/charts/
```

folder.

## 📁 Project Structure

```text
Task-5-Statistical-Analysis/
│
├── dataset/
│   ├── StudentsPerformance.csv
│   └── cleaned_students_performance.csv
│
├── notebook/
│   ├── charts/
│   │   ├── math_score_distribution.png
│   │   ├── reading_score_distribution.png
│   │   ├── writing_score_distribution.png
│   │   ├── average_scores_by_gender.png
│   │   ├── test_preparation_scores.png
│   │   ├── score_correlation_heatmap.png
│   │   ├── student_scores_boxplot.png
│   │   ├── parental_education_scores.png
│   │   ├── average_scores_by_lunch.png
│   │   ├── test_preparation_distribution.png
│   │   ├── gender_distribution.png
│   │   ├── overall_score_distribution.png
│   │   └── subject_average_scores.png
│   │
│   ├── reports/
│   │   ├── statistical_summary.csv
│   │   ├── correlation_matrix.csv
│   │   ├── gender_analysis.csv
│   │   ├── test_preparation_analysis.csv
│   │   ├── parental_education_analysis.csv
│   │   ├── final_report_summary.csv
│   │   └── Statistical_Analysis_Report.pdf
│   │
│   └── task5_statistical_analysis.ipynb
│
├── README.md
└── requirements.txt
```

## 📈 Key Findings

* Reading has the highest average score among the three subjects.
* Math has the lowest average score among the three subjects.
* Reading and Writing scores have a strong positive correlation.
* Student performance can be compared across gender, lunch type, test preparation course, and parental education.
* Statistical tests were performed using a significance level of **0.05**.

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project

```bash
cd Task-5-Statistical-Analysis
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook from the `notebook` folder and run the cells sequentially.

## 📄 Report

The final statistical analysis report is available as:

```text
notebook/reports/Statistical_Analysis_Report.pdf
```

## 🎯 Objective

The main objective of this project is to demonstrate practical statistical data analysis using Python libraries and to extract meaningful insights from student performance data.
