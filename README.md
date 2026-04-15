# 🎓 Student Performance Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict student academic performance based on lifestyle and behavioural factors such as study habits, sleep duration, stress levels, and screen time.

Using machine learning techniques, the project identifies key factors influencing performance and builds models to:
- Predict exam scores (regression)
- Classify students as pass/fail (classification)

---

## 🎯 Objectives
- Analyze the relationship between lifestyle factors and academic performance  
- Build predictive models for student exam scores  
- Identify key features affecting student success  
- Provide data-driven insights for improving academic outcomes  

---

## 📊 Dataset Description
The dataset contains approximately **80,000 student records** with features including:
- Study hours per day  
- Sleep duration  
- Stress levels  
- Social media usage  
- Previous GPA  
- Attendance percentage  
- Screen time  

**Target Variable:**
- `exam_score` (continuous)

---

## 🛠️ Data Preprocessing
- Handled missing values using mean imputation  
- Converted categorical variables using one-hot encoding  
- Removed irrelevant features (e.g., student IDs)  
- Applied feature scaling (standardization)  

---

## 📈 Exploratory Data Analysis (EDA)
- Correlation heatmaps to identify relationships  
- Scatter plots to analyze trends  
- Feature importance analysis  

### Key Insights:
- 📚 Study hours and previous GPA positively impact performance  
- 😴 Sleep duration improves academic outcomes  
- 😓 Stress and screen time negatively affect scores  

---

## 🤖 Machine Learning Models

### 1. Linear Regression
- Used to predict exam scores  
- **R² Score:** 0.8704  
- **MSE:** 17.55  

### 2. Logistic Regression
- Used for pass/fail classification  
- **Accuracy:** 99.83%  

### 3. Random Forest (Comparison)
- **R² Score:** 0.8683  
- **MSE:** 17.83  

---

## 📊 Model Evaluation
- Train-test split (80/20)  
- 5-fold cross-validation  
- Metrics used:
  - R² Score  
  - Mean Squared Error (MSE)  
  - Accuracy  
  - Confusion Matrix  

---

## 🔍 Results & Findings
- Student performance can be predicted with high accuracy  
- Linear relationships dominate the dataset  
- Lifestyle factors significantly influence academic success  
- Models show strong generalization across unseen data  

---

## 💡 Recommendations
- Implement early warning systems for at-risk students  
- Provide mental health and stress management support  
- Encourage better sleep and reduced screen time  
- Offer personalized study plans  

---

## 🧰 Tech Stack
- Python 🐍  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 📂 Project Structure
├── data/
├── notebooks/
├── models/
├── results/
├── README.md
└── requirements.txt

---


---

## 🚀 How to Run
1. Clone the repository  
```bash
git clone https://github.com/your-username/student-performance-prediction-ml.git

2. Navigate to the project folder
```bash
cd student-performance-prediction-ml

3. Install dependencies
4. Run the notebook
