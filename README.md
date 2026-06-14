# 🎓 Student Performance Analysis

## About This Project

Schools often struggle to identify students who may be at risk of poor academic performance before final examinations. In this project, I analyzed a dataset of 1000 students to understand how factors such as parental education, gender, and test preparation influence academic outcomes.

The primary objective was to identify at-risk students and provide data-driven recommendations that could help improve overall student performance.

---

## Dataset Overview

* Records: 1000 Students
* Features: 8
* Missing Values: 0
* Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

### Dataset Features

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

---

## Project Workflow

### 1. Data Exploration & Cleaning

* Loaded and inspected the dataset
* Checked data types and structure
* Verified missing values
* Generated descriptive statistics

### 2. Factor Analysis

Investigated:

* Impact of parental education on student scores
* Effectiveness of test preparation courses
* Correlation among subjects
* Gender-based performance differences
* Distribution of overall scores

### 3. Student Risk Analysis

Defined an at-risk student as:

> Any student scoring below 50 in at least one subject.

---

## Visualizations Created

✔ Box Plot – Parental Education vs Math Score

✔ Bar Chart – Test Preparation Comparison

✔ Correlation Heatmap

✔ Gender vs Subject Performance

✔ Total Score Distribution Histogram

✔ Reading Score vs Math Score Scatter Plot

---

## Key Insights

###  Parental Education Influences Performance

Students whose parents hold Bachelor's or Master's degrees generally achieved higher academic scores.

###  Test Preparation Has a Significant Impact

Students who completed the test preparation course consistently outperformed those who did not.

| Test Preparation | Math  | Reading | Writing |
| ---------------- | ----- | ------- | ------- |
| Completed        | 69.70 | 73.89   | 74.42   |
| None             | 64.08 | 66.53   | 64.50   |

###  Reading and Writing Skills Are Closely Related

Correlation between Reading and Writing Scores:

**0.95**

This indicates a very strong positive relationship.

###  Gender-Based Differences Exist

* Male students performed better in Mathematics.
* Female students performed better in Reading and Writing.

---

## At-Risk Student Segmentation

### Overall Risk

| Status      | Students |
| ----------- | -------- |
| At Risk     | 188      |
| Not At Risk | 812      |

### Risk Percentage

**18.8%** of students were identified as academically at risk.

### Risk by Gender

| Gender | At-Risk % |
| ------ | --------- |
| Female | 17.18%    |
| Male   | 20.54%    |

### Risk by Test Preparation

| Test Preparation | At-Risk % |
| ---------------- | --------- |
| Completed        | 10.06%    |
| None             | 23.68%    |

---

## Recommendations

1. Expand access to test preparation programs.
2. Identify struggling students earlier through regular assessments.
3. Provide additional academic support for at-risk students.
4. Encourage stronger parental involvement in student learning.

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Statistical Analysis
* Correlation Analysis
* Data Visualization
* Business Insights & Reporting
* Risk Segmentation

---

## Conclusion

The analysis revealed that test preparation and parental education are two of the most influential factors affecting student performance. Nearly one in five students was classified as academically at risk. Implementing targeted intervention programs and expanding access to preparation resources can help schools improve student outcomes and reduce academic risk.
