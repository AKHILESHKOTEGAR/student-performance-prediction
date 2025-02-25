# 🎓 Predictive Analysis of Student Performance

## 📌 Overview
A data-driven approach to predict student performance using socioeconomic and academic data. This project focuses on identifying key factors that influence success and utilizes machine learning techniques for predictive modeling.

## 📊 Dataset
- **Source:** UCI Machine Learning Repository
- **Files Used:** `student-mat.csv` (Mathematics) & `student-por.csv` (Portuguese)
- **Features:** Demographics, family background, academic records, study time, parental education, previous grades, and social factors.

## ⚙️ Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Model Used:** Random Forest Classifier

## 🧮 Methodology
1. **Data Preprocessing:**
   - Merged both datasets for comprehensive analysis.
   - Handled missing values and duplicates.
   - Encoded categorical variables and engineered features.

2. **Exploratory Data Analysis (EDA):**
   - Correlation analysis using heatmaps.
   - Visualized grade distributions and socioeconomic impacts.

3. **Model Building:**
   - Implemented Random Forest Classifier.
   - Achieved an accuracy of **92.21%**.
   - Evaluated using confusion matrix, precision, recall, and F1-score.

4. **Feature Importance:**
   - Identified top influencing factors like previous grades, study time, and parental education.

## 📈 Results
- **Accuracy:** 92.21%
- **Key Insights:**
  - Academic factors (e.g., previous grades, study time) heavily influence student performance.
  - Socioeconomic background, including parental education, plays a crucial role.
  - High absenteeism and previous failures negatively impact final grades.

## 🎯 Conclusion
The predictive model effectively identifies students at risk of underperforming, allowing for targeted academic support. This analysis can assist educators in designing interventions for student success.

## 🚀 Future Work
- Apply advanced models like **XGBoost** and **Gradient Boosting**.
- Conduct time-series analysis to track performance trends.
- Expand the dataset for more generalized insights.

## 📖 References
- [UCI Machine Learning Repository - Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- Scikit-learn Documentation
- Seaborn & Matplotlib Documentation

---

💡 *Feel free to fork this repository and experiment with different models or feature engineering techniques!*

