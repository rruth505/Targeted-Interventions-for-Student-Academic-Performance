# Student Academic Performance Analysis

## Overview

This project explores the factors that influence student academic achievement using exploratory data analysis (EDA), statistical testing, and machine learning. The objective is to identify which demographic and socioeconomic variables most strongly impact student performance in mathematics, reading, and writing and demonstrate how data-driven insights can guide targeted educational interventions.

The analysis investigates how variables such as gender, race/ethnicity, parental education level, lunch type, and test preparation completion relate to standardized test scores while comparing multiple predictive models to forecast student performance.

---

## Business Problem

Educational institutions often struggle to identify students who may be at risk of lower academic performance before intervention opportunities are missed.

This project answers the question:

> **Which student background factors most strongly influence academic performance, and how can those insights be used to improve educational outcomes?**

The results can help educators and policymakers prioritize resources, develop targeted support programs, and reduce achievement gaps.

---

## Dataset

**Student Academic Performance Dataset**

The dataset contains student demographic information along with standardized test scores.

### Features

- Gender
- Race/Ethnicity
- Parental Education Level
- Lunch Type
- Test Preparation Course Completion

### Target Variables

- Math Score
- Reading Score
- Writing Score

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

- Loaded and explored the dataset
- Renamed columns for consistency
- Checked for missing values
- Generated descriptive statistics
- Prepared categorical features for modeling

---

### 2. Exploratory Data Analysis (EDA)

Visualizations included:

- Distribution plots
- Boxplots
- Group comparisons
- Average score comparisons
- Feature distributions

EDA explored relationships between:

- Gender
- Race/Ethnicity
- Parental Education
- Lunch Type
- Test Preparation

---

### 3. Statistical Analysis

Performed hypothesis testing using:

- Independent t-tests
- ANOVA

to determine whether differences between groups were statistically significant.

---

### 4. Machine Learning Models

Implemented multiple regression models to predict student performance.

Models included:

- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression

Each model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Cross-validation

---

### 5. Feature Importance

Random Forest feature importance was used to determine which variables contributed most to student performance.

Top predictors included:

- Lunch Type
- Test Preparation Completion
- Gender
- Race/Ethnicity
- Parental Education

---

## Key Findings

### Test Preparation Matters

Students who completed a test preparation course consistently achieved higher scores across all subjects.

### Lunch Type Was the Strongest Predictor

Lunch type emerged as the most influential predictor, suggesting socioeconomic factors play an important role in academic achievement.

### Parental Education Influences Performance

Higher parental education levels were associated with improved student outcomes.

### Writing Scores Were Most Predictable

Among the three academic subjects, writing scores achieved the strongest predictive performance.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Skills

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Testing
- Feature Engineering
- Machine Learning
- Model Evaluation
- Regression Analysis
- Feature Importance Analysis
- Cross Validation
- Educational Data Analytics

---

## Results

The project demonstrates how predictive analytics can uncover meaningful relationships between demographic factors and academic outcomes.

Rather than relying solely on intuition, educational leaders can use these insights to:

- Expand access to test preparation programs
- Identify students who may benefit from additional academic support
- Allocate educational resources more effectively
- Develop evidence-based intervention strategies
- Promote greater educational equity

---

## Future Improvements

Potential enhancements include:

- Hyperparameter tuning
- SHAP model explainability
- Student performance classification
- Interactive dashboards using Power BI or Tableau
- Deployment as a predictive web application

---

## Author

**Ruth Maddux**

Certified Occupational Therapy Assistant transitioning into Healthcare Data Analytics, leveraging data-driven solutions to solve complex real-world problems.

