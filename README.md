# Life Expectancy Analysis using Machine Learning

---

## Project Overview

This project analyzes global life expectancy using Machine Learning to uncover the key factors affecting human lifespan.

It leverages health, economic, and social data from 193 countries (2000–2015) to build predictive models and generate actionable insights.

---

## Objectives

* Identify factors affecting life expectancy
* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA)
* Build and evaluate ML models
* Generate meaningful insights

---

## Project Workflow

* Data Collection
* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Model Training
* Model Evaluation

---

## Dataset

* Source: WHO and United Nations
* Countries: 193
* Years: 2000 – 2015
* Rows: 2938
* Features: 22

### Key Features:

* GDP
* Schooling
* Adult Mortality
* Infant Deaths
* Healthcare Expenditure
* Immunization

---

## Exploratory Data Analysis

* Life Expectancy Distribution
* Correlation Heatmap

---

## Machine Learning Models

| Model             | Description                       |
| ----------------- | --------------------------------- |
| Random Forest     | Ensemble model with high accuracy |
| Extra Trees       | Faster variant of Random Forest   |
| Gradient Boosting | Sequential improvement            |
| XGBoost           | High-performance boosting model   |

---

## Model Performance

* Best Model: XGBoost / Random Forest
* R² Score: ~0.95+
* RMSE: Low

---

## Key Insights

* GDP strongly influences life expectancy
* Education improves lifespan significantly
* Mortality rates negatively impact life expectancy
* Healthcare spending increases longevity
* Immunization improves survival rates
* Developed countries have higher life expectancy

---

## Project Structure

```id="h2d9ks"
Life-Expectancy-Analysis-ML-Project/
│
├── Life_Expectancy_Project_FIXED.ipynb
├── Life Expectancy Data.csv
├── Life_Expectancy_Presentation.pptx
├── README.md
```

---

## How to Run

```id="xk39sl"
git clone https://github.com/unmeshup/Life-Expectancy-Analysis-ML-Project.git
cd Life-Expectancy-Analysis-ML-Project
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
jupyter notebook
```

---

## Project Demo

* Notebook: (Add Colab/GitHub link)
* Presentation: (Add Drive link)
* Video: (Add your video link)

---

## Conclusion

Life expectancy is driven by a combination of economic, healthcare, and social factors.

Improving:

* Education
* Healthcare
* Economic conditions

can significantly enhance lifespan globally.

---

## Acknowledgements

* World Health Organization (WHO)
* United Nations
* Kaggle Dataset Contributors

---

## Show your support

If you like this project, give it a star on GitHub.

---

## Future Improvements

* Interactive dashboard (Streamlit)
* Model deployment (API)
* Advanced feature importance analysis
