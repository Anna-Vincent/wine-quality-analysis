
# Wine Quality Analysis (EDA)

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the Wine Quality dataset to identify key physicochemical factors that influence wine quality. The goal is to extract meaningful insights using statistical analysis and visualization techniques.

---

## 🎯 Objectives

* Understand the structure and distribution of wine data
* Identify relationships between chemical properties and quality
* Detect outliers and data patterns
* Derive actionable insights for quality prediction

---

## 📊 Dataset

* Source: Kaggle
* Records: 1,500+ red wine samples
* Features: 11 physicochemical attributes (e.g., alcohol, acidity, sulphates)
* Target Variable: Wine quality (score between 0–10)

---

## 🛠️ Tools & Technologies

* **Python**

  * Pandas, NumPy → Data manipulation
  * Matplotlib, Seaborn → Data visualization

---

## 🔍 Key Analysis Performed

* Data cleaning (handling duplicates, validation)
* Univariate analysis (feature distributions)
* Correlation analysis (heatmap)
* Feature vs target relationships
* Outlier detection using IQR method

---

## 📈 Key Insights

* **Alcohol** has a strong positive correlation with wine quality
* **Volatile acidity** negatively impacts quality
* Most wines fall within **quality scores 5–6**, indicating class imbalance
* Certain features (like sulphates and residual sugar) contain outliers
* Chemical composition plays a significant role in determining perceived quality

---

## 📁 Project Structure

```
wine-quality-analysis/
│── Wine_Quality_EDA.ipynb
│── README.md
│── dataset/ (optional or external link)
```

---

## 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/wine-quality-analysis.git
   ```
2. Install dependencies

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the notebook in Jupyter/Colab

---

## 📌 Future Improvements

* Build a **machine learning model** to predict wine quality
* Perform feature engineering for improved accuracy
* Deploy as an interactive dashboard (Power BI / Streamlit)

---

## 👩‍💻 Author

**Anna Vincent**

* GitHub: https://github.com/annavincent
* LinkedIn: https://www.linkedin.com/in/anna-vincent-138996244 

---
