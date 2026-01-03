#  Tax Awareness Among Students: A Data-Driven Analysis Using Machine Learning

##  Project Overview
Taxation is the backbone of a nation’s economy, supporting essential services such as education, healthcare, security, and infrastructure.  
Despite its importance, many students lack proper awareness of income tax rules, tax-saving schemes, and filing procedures.

This project analyzes the **level of tax awareness among college students (18+ years)** in the **Pune District** using **statistical analysis and machine learning techniques**.

---

##  Objectives
- To assess students’ awareness of income tax concepts and tax-saving schemes  
- To identify factors influencing tax knowledge among students  
- To apply statistical tests and machine learning models for deeper insights  
- To classify students into awareness groups using clustering  

---

##  Data Collection
- **Data Source:** Primary data collected through a structured **Google Form survey**
- **Target Group:** College students aged 18 years and above
- **Location:** Pune District
- **Key Topics Covered:**
  - Income tax slabs  
  - Section 80C deductions  
  - Tax-saving instruments (PPF, ELSS, LIC, etc.)  
  - Tax filing practices  
  - Challenges in tax planning  

---

##  Data Preprocessing
- Handled missing values using appropriate imputation methods  
- Encoded categorical variables into numerical form  
- Created an **Overall Awareness Score**  
- Standardized data before applying machine learning models  

---

##  Statistical Analysis
The following statistical techniques were applied:
- **Descriptive Statistics** – to summarize awareness levels  
- **Chi-Square Test** – to study associations between categorical variables  
- **Kruskal-Wallis Test** – to compare awareness levels across different groups  

---

##  Machine Learning Models
The project uses multiple machine learning models to predict tax awareness levels:

| Model                 | Purpose                          | R² Score |
|----------------------|----------------------------------|---------|
| Linear Regression    | Baseline model                   | -0.1219 |
| Polynomial Regression| Captures non-linear patterns     | 0.6284  |
| Ridge Regression     | Regularized regression           | 0.8515  |
| Lasso Regression     | Feature selection & prediction   | 0.8696  |


 **Best Model:** Lasso Regression  
 **Performance:** R² score of **0.8696**

---

##  Clustering Analysis
- Applied **K-Means Clustering** to group students into:
  - Low Awareness  
  - Moderate Awareness  
  - High Awareness  
- Used **PCA (Principal Component Analysis)** for 2D visualization of clusters  

---

##  Key Findings
- Students from **Commerce backgrounds** showed the highest tax awareness  
- **Science and Arts students** had limited understanding of tax-saving instruments  
- Many students had **theoretical knowledge** but lacked **practical experience** in tax filing  
- Awareness of **Section 80C schemes** was moderate  
- Students with **family exposure to tax filing** demonstrated higher awareness  

---

##  Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
- **Techniques:**  
  - Statistical testing  
  - Regression modeling  
  - Clustering (K-Means)  
  - Dimensionality reduction (PCA)  

---

##  Conclusion
The study highlights a **moderate level of tax awareness among students**, with noticeable gaps in practical tax knowledge.  
Introducing **basic tax education at the college level** can significantly improve financial literacy and long-term compliance.

---
