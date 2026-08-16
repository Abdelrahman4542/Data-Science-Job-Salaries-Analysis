# Data Science Job Salaries Analysis

## 📌 Project Overview

This project analyzes a dataset of Data Science job salaries to understand salary patterns and identify the main factors associated with differences in compensation.

The project was developed as our first graduation project during the **Samsung Innovation Campus – AI Track**.

Our analysis focuses on exploring salary differences across:

- Experience Level
- Job Title
- Company Size
- Company Location
- Remote Work Arrangement
- Work Year
- Salary Currency

The project combines **Exploratory Data Analysis (EDA), Statistical Analysis, and Interactive Data Visualization using Power BI**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Understand the structure and characteristics of the dataset.
- Perform data cleaning and preprocessing.
- Explore salary distributions and identify potential outliers.
- Analyze salary differences across experience levels and job roles.
- Compare salaries across company sizes and locations.
- Investigate salary trends over time.
- Compare Data Scientists and Data Analysts.
- Analyze relationships between numerical variables.
- Present the main findings through an interactive Power BI dashboard.

---

## 🔍 Exploratory Data Analysis

My main responsibility in the project was the **Exploratory Data Analysis (EDA)**.

The EDA focused on understanding the data, asking relevant research questions, identifying patterns and relationships, and transforming the results into meaningful insights.

The analysis included:

- Descriptive statistics
- Mean, Median, and Standard Deviation
- Salary distribution analysis
- Histogram analysis
- Boxplot and outlier analysis
- Salary comparison by job title
- Salary comparison by experience level
- Salary analysis by company location
- Salary analysis by company size
- Remote-work salary analysis
- Salary trends over time
- Correlation analysis

---

## ❓ Research Questions

The analysis was guided by the following questions:

1. Does salary increase with experience level?
2. Which job titles have the highest typical salaries?
3. Does company size relate to salary?
4. Do salaries differ by remote-work arrangement?
5. Which company locations have higher salaries?
6. How do salaries change over the available years?
7. Is there a salary difference between Data Scientists and Data Analysts?

---

## 📊 Key Findings

Some of the main findings from the analysis include:

- Salary generally increases with experience level.
- Data Architect had the highest median salary among the selected job roles.
- Small companies showed lower typical salaries compared with medium and large companies.
- Fully remote roles showed higher salary levels in the analyzed sample.
- The US had the highest median salary among sufficiently represented locations.
- Salary levels increased from 2020 to 2022.
- Data Scientists had higher salary levels than Data Analysts in the analyzed sample.
- The numerical correlations with salary were relatively weak, suggesting that salary differences are associated with a combination of factors rather than a single numerical variable.

---

## 📈 Statistical Analysis

Descriptive statistics were used to summarize the salary distribution.

- **Mean Salary:** approximately $112,298
- **Median Salary:** approximately $101,570
- **Standard Deviation:** approximately $70,957

The mean being higher than the median indicates a **right-skewed salary distribution**, influenced by relatively high-paying observations.

Potential outliers were inspected using boxplots and were retained because they could not be confirmed as data-entry errors.

### Correlation Findings

The main numerical correlations were:

| Relationship | Correlation |
|---|---:|
| Salary vs. Work Year | 0.170 |
| Salary vs. Remote Ratio | 0.132 |
| Work Year vs. Remote Ratio | 0.076 |

Overall, the correlations were weak, and no strong linear relationship with salary was observed among the analyzed numerical variables.

---

## 📊 Power BI Dashboard

The analysis was also presented through an interactive **Power BI dashboard**.

The dashboard includes:

- Salary KPIs
- Average Salary
- Median Salary
- Highest Salary
- Number of Jobs
- Salary distribution
- Salary by experience level
- Salary by company location
- Salary by remote-work arrangement
- Salary trends by year
- Salary comparison by job title
- Company size analysis
- Data Scientist vs. Data Analyst comparison

The dashboard also includes interactive filters to allow users to explore the results from different perspectives.

---

## 🧩 Data Model

The Power BI model follows a **Star Schema** consisting of:

- `Fact`
- `Employment_Dim`
- `Company_Dim`

Core DAX measures include:

- `Average_Salary`
- `Median_Salary`
- `Highest_Salary`
- `Total_Salary`
- `numb_job`

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- DAX
- Data Modeling
- Exploratory Data Analysis
- Statistical Analysis

---

## 📁 Project Structure

```text
Data-Science-Job-Salaries-Analysis/
│
├── README.md
│
├── EDA/
│   └── Data_Science_Salaries_EDA.ipynb
│
├── PowerBI/
│   └── Data_Science_Job_Salaries.pbix
│
├── Presentation/
│   └── Project_Presentation.pdf
│
└── Data cleaning/
    └── cleaned_dataset.csv
