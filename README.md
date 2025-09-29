Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

Overview
This repository contains the submission for **Task 5: Exploratory Data Analysis (EDA)** as part of the **Data Analyst Internship**.  
The objective of this task was to perform **visual and statistical exploration** on the Titanic dataset and extract meaningful insights.  

Objectives
- Perform EDA on the Titanic dataset (or a relevant dataset).  
- Use **Pandas, Matplotlib, and Seaborn** for data analysis and visualization.  
- Identify missing values, outliers, relationships, and trends.  
- Generate visualizations such as histograms, boxplots, scatterplots, heatmaps, and pairplots.  
- Write observations for each analysis/visualization.  
- Summarize findings in a structured PDF report.

Dataset
Dataset used: Titanic Dataset from Kaggle  


- Rows: **891**  
- Columns: **12**  
- Features include: Passenger ID, Name, Age, Sex, Class, Fare, Cabin, Embarked, and Survival status.  

Analysis Performed
- **Data Inspection** → `.info()`, `.describe()`, `.value_counts()`  
- **Missing Value Analysis** → Identified missing data in *Age, Cabin, Embarked*  
- **Univariate Analysis** → Histograms, bar plots for Age, Sex, Pclass, Fare  
- **Bivariate Analysis** → Survival rate vs Gender, Age groups, and Class  
- **Multivariate Analysis** → Heatmap, pairplot for correlations and relationships  
- **Summary Statistics** → Mean, median, and distribution insights  

Key Findings
- Average passenger age: **29.7 years**  
- Average fare: **32.2 units**  
- Survival rate: **~38%**  
- More passengers in **3rd class** compared to 1st/2nd  
- **Females and children** had higher survival rates  
- Higher survival chances for passengers in higher classes  
- Cabin data is largely missing → **687 out of 891 entries**    

Tools & Libraries
- Python 3  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- ReportLab (for PDF report generation)  
