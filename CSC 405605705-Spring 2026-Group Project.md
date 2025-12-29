---
title: Project
nav_order: 5
last_modified_date: true
---

# Data Science Group Project

## 1. Project Overview

This course does not have a final exam. Instead, students will complete a **team-based data science project**. Students should form groups of **3–4 members**. Working alone is allowed but not recommended.

- The project applies the full pipeline covered in this course: 
  - data acquisition
  - data cleaning
  - exploratory analysis & statistical reasoning
  - modeling
  - visualization
  - report & presentation

- Each team will:

  - Select **one dataset** from the approved list

  - Formulate their **own data-driven problem**: Define the target variables and the type of problem (e.g., regression, classification, clustering)

  - Apply **required analytical components** described below

  - Present results in a **final report & presentation**

​       Each team creates **one shared GitHub repository** and add instructor as a collaborator.

## 2. Required Project Components (All Teams Must Complete)

### (1) Reproducible Data Science Workflow (15%)

Your project **must be reproducible**.

**Required:**

- Public or private GitHub repository (**invite instructor as collaborator**)

- Clear folder structure, e.g.:

  ```
  data/ # put your dataset here
  notebooks/ # you can use a notebook for communication
  src/  # put your code here
  figures/ # put figure here
  report/ # put your final report here
  ```

- README file **must** include:

  - Team name & team members (full names, emails, and GitHub usernames)
  - Project title
  - Dataset source (website link) 
  - Brief project description – What problems are planned to be studied, including which aspects.

Version control usage will be evaluated (**GitHub commit history** and **individual contribution traces** will be considered during grading).

### (2) Data Cleaning & Exploratory Data Analysis (EDA) (20%)

You **must** demonstrate:

- Identification and handling of missing values
- Detection of outliers or anomalies
- Use of:
  - Group-by / aggregation
  - Descriptive statistics

Simply dropping data without justification is not acceptable.

### (3) Statistical Analysis & Hypothesis Testing (20%)

You **must** perform **at least one formal statistical analysis**, such as:

- t-test
- ANOVA
- Chi-square test
- Correlation tests for numerical features

For each test:

- State the null hypothesis (default assumption)
- Explain why the test is appropriate
- Report test statistic and p-value
- Interpret the result in context

### (4) Data Modeling (20%)

You **must** implement:

- **One baseline model**: Logistic Regression, Decision Tree, Linear Regression;
- **One more advanced model**: Random Forest, XGBoost, LightGBM, Neural Networks;

Deep learning models are **not required**. For time-series datasets: LSTM, GRU, Prophet can be used.

### (5) Visualization (15%)

Your project must include **at least five figures**, covering:

- Data exploration
- Statistical analysis
- Model results
- Final insights

**At least one** figure should be:

- Multi-panel, or
- Interactive (e.g., Plotly, Altair)

Figures must be readable, labeled, and interpreted.

### (6) Final Report & Presentation (10%)

- Written report (PDF or Markdown, **Jupyter notebook is highly recommended**): No length requirement.
- Clear structure and logical flow
- Final presentation during Weeks 15–16, each group will deliver an in-class presentation of approximately 15–20 minutes.

## 3. Academic Integrity and Use of AI Tools

The use of AI tools is **allowed** when used responsibly for **learning purposes** such as understanding concepts, debugging code or understanding error messages. However, all submitted work must reflect the **students’ own understanding**. Students are expected to write and modify code by hand, make independent analytical decisions, and fully understand the methods and results they present. During project presentations, students may be asked to explain any part of their report, code, or analysis; **inability to clearly explain submitted work will result in grade penalties**, including partial credit loss or individual score adjustments. 

## 4. Datasets

- Fast Food Consumption & Health Impact Dataset

  https://www.kaggle.com/datasets/prince7489/fast-food-consumption-and-health-impact-dataset

- Career Path Recommendations Dataset

  https://www.kaggle.com/datasets/ahsanneural/career-path-recommendations-dataset?resource=download

- Breast Cancer Dataset

  https://www.kaggle.com/datasets/neurocipher/breast-cancer-dataset

- EuroMillions Historical Data

  https://www.kaggle.com/datasets/duartepereiradacruz/euromillions-historical-data

- Delivery Logistics Dataset

  https://www.kaggle.com/datasets/muhammadahmaddaar/delivery-logistics-dataset-india-multi-partner

- Synthetic Diabetes Prediction Dataset

- https://www.kaggle.com/datasets/miadul/synthetic-diabetes-prediction-dataset

- Student Placement Dataset

  https://www.kaggle.com/datasets/sonalshinde123/student-placement-dataset

- Hospital Readmission Risk dataset

  https://www.kaggle.com/datasets/miadul/hospital-readmission-risk-dataset

- Dirty Iranian Transactions Dataset

  https://www.kaggle.com/datasets/hosseinbadrnezhad/dirty-iranian-transactions-dataset

- Customer Churn Dataset

  https://www.kaggle.com/datasets/sonalshinde123/customer-churn-prediction-dataset

- Crop Yield Prediction

  https://www.kaggle.com/datasets/miadul/smart-crop-recommendation-dataset

- COVID-19 Patient Symptoms & Diagnosis Dataset

  https://www.kaggle.com/datasets/miadul/covid-19-patient-symptoms-and-diagnosis-dataset

- Fertilizer Recommendation Dataset

  https://www.kaggle.com/datasets/miadul/fertilizer-recommendation-dataset

- Synthetic Credit Risk Dataset 

  https://www.kaggle.com/datasets/emirhanakku/synthetic-credit-risk-dataset-extreme-imbalance