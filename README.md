# 🏥 Public Health Inferential Statistics Project

## 📌 Project Title
**Statistical Analysis of Health Factors Affecting Disease Occurrence**

---

## 📖 Project Overview
This project applies **inferential statistical techniques** to analyze health records and determine significant factors influencing disease occurrence, specifically **Diabetes** and **Hypertension**.

Using Python libraries such as **NumPy, Pandas, SciPy, and Matplotlib/Seaborn**, the project evaluates hypotheses, computes confidence intervals, performs statistical tests, and interprets results based on real-world public health data.

---

## 🎯 Objective
To apply inferential statistics concepts to:
- Test hypotheses
- Calculate confidence intervals
- Perform statistical significance testing
- Analyze relationships between variables
- Interpret results using p-values and decision rules

---

## 🗂️ Dataset Description

The dataset contains simulated public health records with the following fields:

| Column Name | Description |
|-------------|-------------|
| record_id | Unique health record identifier |
| age_group | Categorized age group |
| age | Age of individual |
| weight | Weight in kg |
| gender | Gender of individual |
| region | Geographic region |
| smoking_status | Smoking habit category |
| exercise_frequency | Exercise frequency |
| bmi | Body Mass Index |
| blood_pressure | Systolic blood pressure |
| diabetes | Diabetes diagnosis (True/False) |
| hypertension | Hypertension diagnosis (True/False) |
| cholesterol_level | Total cholesterol (mg/dL) |
| glucose_level | Fasting glucose (mg/dL) |
| visit_date | Date of health check-up |

Dataset size: **120 records**

---

## 🧪 Statistical Methods Applied

### 1️⃣ Hypothesis Testing
Formulated hypotheses such as:
- Smoking status vs. Diabetes occurrence
- BMI difference between diabetic and non-diabetic individuals

Each test includes:
- Null hypothesis (H₀)
- Alternative hypothesis (H₁)
- Test statistic
- p-value
- Decision rule (Reject/Accept H₀)

---

### 2️⃣ Confidence Intervals
Computed 95% confidence intervals for:
- Age
- Weight

Used **t-distribution** due to sample-based estimation.

---

### 3️⃣ t-Test
Compared mean BMI between:
- Diabetic individuals
- Non-diabetic individuals

Purpose: Determine if mean difference is statistically significant.

---

### 4️⃣ Chi-Square Test
Tested association between:
- Smoking status
- Diabetes occurrence

Used contingency tables to evaluate independence between categorical variables.

---

### 5️⃣ ANOVA (Analysis of Variance)
Analyzed whether:
- Mean glucose levels differ across age groups

Used F-statistic and p-value for significance testing.

---

### 6️⃣ Covariance & Correlation
Calculated:
- Covariance between Age and BMI
- Correlation coefficient between continuous variables

Purpose: Measure strength and direction of linear relationships.

---

## 📊 Tools & Libraries Used

- **NumPy** → Numerical operations
- **Pandas** → Data manipulation & cleaning
- **SciPy** → Statistical testing
- **Matplotlib / Seaborn** → Data visualization

---

## 🧠 Key Findings (Sample Insights)

- Smoking status shows a statistically significant association with diabetes.
- BMI is significantly higher among diabetic individuals.
- Glucose levels vary significantly across age groups.
- Age and BMI show a positive correlation.
- Lifestyle and physiological factors contribute to disease risk.

---

## 📌 Statistical Decision Rule Used

At significance level α = 0.05:
- If **p-value < 0.05** → Reject H₀ (statistically significant)
- If **p-value ≥ 0.05** → Fail to reject H₀

---

## 🏁 Conclusion

This project demonstrates practical application of inferential statistics in public health analysis. By applying hypothesis testing, confidence intervals, ANOVA, chi-square, and correlation analysis, we identified statistically significant relationship
