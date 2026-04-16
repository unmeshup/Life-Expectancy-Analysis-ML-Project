# 🌍 Life Expectancy Analysis using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/unmeshup/Life-Expectancy-Analysis-ML-Project?style=for-the-badge">
</p>

---

## 📌 Project Overview

This project analyzes global life expectancy using **Machine Learning** to uncover the key factors affecting human lifespan.

It leverages health, economic, and social data from **193 countries (2000–2015)** to build predictive models and generate actionable insights.

---

## 🎯 Objectives

✔ Identify factors affecting life expectancy  
✔ Perform data cleaning and preprocessing  
✔ Conduct exploratory data analysis (EDA)  
✔ Build and evaluate ML models  
✔ Generate meaningful insights  

---

## 📊 Project Workflow

<p align="center">
  <img src="https://raw.githubusercontent.com/ritchieng/deep-learning-wizard/master/docs/deep_learning/boosting/boosting_flow.png" width="600">
</p>

---

## 🗂️ Dataset

- 📍 Source: WHO & United Nations  
- 🌎 Countries: 193  
- 📅 Years: 2000 – 2015  
- 📊 Rows: 2938  
- 📌 Features: 22  

### 🔑 Key Features:
- GDP 💰  
- Schooling 🎓  
- Adult Mortality ⚠️  
- Infant Deaths 👶  
- Healthcare Expenditure 🏥  
- Immunization 💉  

---

## 🔍 Exploratory Data Analysis

### 📈 Life Expectancy Distribution
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*e1F9WbH0I1GtIsfRSAxE1w.png" width="500">
</p>

### 🔥 Correlation Heatmap
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*Vn8G8ZrC9XyM54q9WlH0Jg.png" width="500">
</p>

---

## 🤖 Machine Learning Models

| Model | Description |
|------|------------|
| 🌲 Random Forest | Ensemble model with high accuracy |
| 🌳 Extra Trees | Faster variant of Random Forest |
| ⚡ Gradient Boosting | Sequential improvement |
| 🚀 XGBoost | Best performing model |

---

## 📈 Model Performance

✔ **Best Model:** XGBoost / Random Forest  
✔ **R² Score:** ~0.95+  
✔ **RMSE:** Low  

---

## 📊 Key Insights

- 💰 GDP strongly influences life expectancy  
- 🎓 Education improves lifespan significantly  
- ⚠️ Mortality rates negatively impact life expectancy  
- 🏥 Healthcare spending increases longevity  
- 💉 Immunization improves survival rates  
- 🌍 Developed countries have higher life expectancy  

---

## 📁 Project Structure

Life-Expectancy-Analysis-ML-Project/
│
├── 📓 Life_Expectancy_Project_FIXED.ipynb
├── 📊 Life Expectancy Data.csv
├── 📽️ Life_Expectancy_Presentation.pptx
├── 📄 README.md


---

## 🚀 How to Run

```bash
git clone https://github.com/unmeshup/Life-Expectancy-Analysis-ML-Project.git
cd Life-Expectancy-Analysis-ML-Project
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
jupyter notebook

🎥 Project Demo

📘 Notebook: (Add Colab/GitHub link)
📊 Presentation: (Add Drive link)
🎥 Video: (Add your video link)

🧠 Conclusion

Life expectancy is driven by a combination of economic, healthcare, and social factors.

Improving:

Education 🎓
Healthcare 🏥
Economic conditions 💰

can significantly enhance lifespan globally.

🙌 Acknowledgements
WHO 🌍
United Nations
Kaggle Dataset Contributors
⭐ Show your support

If you like this project, give it a ⭐ on GitHub!

🚀 Future Improvements
📊 Interactive dashboard (Streamlit)
🌐 Model deployment (API)
📈 Advanced feature importance analysis
