# 🔧 Plastic Injection Molding Defect Prediction using Machine Learning

> 🏭 Predicting the quality of plastic parts in real-time to optimize manufacturing and reduce waste.

## 📌 Project Overview

This project focuses on improving **plastic injection molding** quality by using **machine learning models** to predict product defects based on process parameters like mold temperature, cycle time, shot volume, etc. The goal is to create a smart, Industry 4.0-ready system that helps factories:

- 🔍 Detect poor quality early
- ⚡ Reduce waste and downtime
- 📈 Improve efficiency and product consistency

We built and compared multiple machine learning models, tuned them using GridSearchCV, and visualized results through an interactive dashboard.

---

## 🧠 Problem Statement

> How can we use machine learning to predict the quality of plastic products during the manufacturing process — and optimize the production setup to reduce defects?

In plastic injection molding, parameters like temperature and cycle time can drastically affect product quality. Traditional post-production inspection is too slow and costly. We solve this using real-time predictive modeling.

---

## 🧪 Machine Learning Models Used

| Model | Accuracy |
|-------|----------|
| 🌲 Random Forest | 96.74% |
| 📈 Logistic Regression | 89% |
| 🧠 Multi-Layer Perceptron (MLP) | 95% |
| ⚡ LightGBM | 96% |
| 🐈 CatBoost | **97%** (Best Performer) |

All models were tuned using `GridSearchCV` and validated with 5-fold cross-validation.

---

## 🔍 Features & Process Parameters

- `Mold Temperature`
- `Cycle Time`
- `Shot Volume`
- `Screw Position`
- `Torque Mean`
- ... and others

These features were used to classify the final product into quality grades (Class 1 to Class 4).

---

## 🛠️ Pipeline Overview

1. **Data Cleaning & EDA**
   - Removed duplicates
   - Checked class balance
   - Standardized numeric features

2. **Statistical Testing**
   - ANOVA & Mood’s Median Test to find impactful parameters

3. **Model Training & Evaluation**
   - Used GridSearchCV for hyperparameter tuning
   - Evaluated using Accuracy, F1-score, Precision, Recall, ROC-AUC

4. **Dashboard Creation**
   - Built an interactive interface for real-time prediction using trained models

---

## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- ROC-AUC Curve
- Confusion Matrix
- Feature Importance

![ROC Example](link-to-your-roc-curve.png) <!-- Add image links if hosted -->

---

## 📉 Feature Importance (Top Predictors)

- `Cycle Time`
- `Mold Temperature`
- `Shot Volume`

These were the most influential features across multiple models.

---

## 💻 Interactive Dashboard

Built using:
- `Streamlit` (or `Dash`, depending on your setup)
- Live prediction using Random Forest or LightGBM
- Visual feedback with confusion matrix, feature importance, and metrics

> Users input process parameters → Dashboard predicts quality → Engineers take action

---

## 🚀 Deployment Ready

Want to deploy?
- Export trained model using `joblib`
- Build a `Streamlit` app or REST API (e.g., Flask)
- Host on Streamlit Cloud, Render, or Hugging Face Spaces

---

## 🧰 Tech Stack

- Python
- scikit-learn
- LightGBM
- CatBoost
- matplotlib & seaborn
- pandas & numpy
- GridSearchCV
- ANOVA (scipy.stats)
- Streamlit (for dashboard)

---

## 📚 References

- Research papers on injection molding defect prediction
- ML documentation: scikit-learn, LightGBM, CatBoost
- [Your university module or supervisor name if applicable]

---

## 🙋 About Me

Hey! I'm **Manpreet Sharma**, an aspiring Data Scientist with a passion for real-world ML applications in manufacturing, finance, and business optimization.

📫 Reach me on:  
- GitHub: [github.com/Manpreet2001-png](https://github.com/Manpreet2001-png)  
- LinkedIn: [linkedin.com/in/manpreet-sharma-b23a41306](https://www.linkedin.com/in/manpreet-sharma-b23a41306)  
- Email: manpreetsingh000445@gmail.com

---

## ✅ Project Status

- [x] ML pipeline complete
- [x] Models evaluated and compared
- [x] Interactive dashboard created
- [ ] Deployment (Coming soon...)

---

