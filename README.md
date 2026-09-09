# 🌾 Seasonal Agriculture Performance Analysis

## Major Data Analytics Project

**Domain:** Agriculture  
**Project Theme:** Seasonal Agriculture Performance  
**Project Type:** Data Analytics Project with Machine Learning & Dashboard Enhancements  
**Development Environment:** Jupyter Notebook / Google Colab

---

## 📌 Project Overview

The **Seasonal Agriculture Performance Analysis** project studies how agricultural performance varies across different seasons and related agricultural conditions.

The project uses a complete **Data Analytics workflow** to transform raw agricultural records into meaningful insights by examining:

- Seasonal performance
- Crop performance
- State and district performance
- Environmental conditions
- Soil and nutrient characteristics
- Irrigation and resource usage
- Water efficiency
- Disease and pest risk
- Production, revenue, cost, and profit
- Relationships, variations, and unusual observations

The core of the project is **Data Analytics**.  
**Machine Learning** and an **Agriculture Performance Dashboard** are included as enhancements to extend the analytical study and present the results more effectively.

---

## 🎯 Project Goal

To investigate how agricultural performance varies across seasons and identify meaningful:

- Patterns
- Trends
- Relationships
- Variations
- Differences

within the available agricultural data.

---

## ❗ Problem Statement

Agricultural performance can vary because of seasonal environmental conditions, crop selection, farming practices, resource availability, disease and pest risk, and economic factors.

Raw agricultural data does not directly explain how agricultural performance changes from one season to another or how different agricultural characteristics are associated with outcomes.

This project therefore analyzes the available dataset to understand seasonal agricultural performance and generate evidence-based insights, conclusions, and recommendations.

---

## 🎯 Objectives

The project aims to:

1. Understand and explore the agricultural dataset.
2. Clean and prepare the data for analysis.
3. Examine agricultural performance across seasons.
4. Identify important seasonal patterns and trends.
5. Compare crop performance across seasons.
6. Compare performance across states and districts.
7. Analyze environmental and soil conditions.
8. Examine irrigation and resource usage.
9. Analyze water efficiency.
10. Study disease and pest risk.
11. Analyze production, revenue, cost, and profitability.
12. Investigate relationships using correlation analysis.
13. Test seasonal differences using statistical methods such as ANOVA.
14. Identify unusual observations through outlier analysis.
15. Create meaningful visualizations for interpretation.
16. Extend the analysis with Machine Learning yield prediction.
17. Classify agricultural records into Low, Medium, and High performance groups.
18. Compare and evaluate Machine Learning models.
19. Identify useful predictive features.
20. Present major results through a dashboard.
21. Develop data-driven insights, conclusions, and recommendations.

---

## 📊 Dataset

The project dataset contains **4,000 records and 28 original columns**.

The notebook works with information covering:

### Geographic Information
- Farm ID
- State
- District

### Agricultural Information
- Crop
- Season
- Farm area

### Environmental Conditions
- Rainfall
- Average temperature
- Humidity
- Sunlight hours

### Soil & Nutrient Information
- Soil pH
- Soil moisture
- Nitrogen
- Phosphorus
- Potassium

### Farming Inputs
- Irrigation method
- Fertilizer usage
- Pesticide usage
- Seed quality

### Agricultural Outcomes
- Yield
- Production
- Market price

### Economic Information
- Total cost
- Revenue
- Profit

### Resource & Risk Information
- Water used
- Water efficiency
- Disease/pest risk

The notebook loads the dataset from:

```text
seasonal_agriculture_performance_dataset.csv
```

---

## 🧹 Data Analytics

The core analytics workflow includes:

### Data Understanding
- Dataset shape
- Column names
- First and last records
- Data types
- Dataset information
- Statistical summary

### Data Cleaning & Preprocessing
- Missing-value analysis
- Duplicate analysis
- Farm ID checks
- Text cleaning
- Numeric conversion
- Missing-value treatment
- Basic validity checks

### Exploratory Data Analysis
- Season distribution
- Crop distribution
- State distribution
- Season-wise performance
- Crop × season analysis
- Regional analysis
- Irrigation analysis
- Water-efficiency analysis
- Environmental relationships
- Soil and nutrient relationships
- Risk analysis
- Economic analysis

### Statistical Analysis
- Correlation analysis
- Correlation with yield
- Correlation with profit
- One-way ANOVA
- Outlier detection using IQR

### Feature Engineering
The notebook also derives useful analytical measures such as:

- Revenue per hectare
- Profit per hectare
- Cost per hectare
- Profit margin
- Calculated yield

---

## 🤖 Machine Learning Enhancement

Machine Learning extends the Data Analytics workflow with prediction and classification.

### 🌾 Yield Prediction

The target variable is:

```text
Yield_Tonnes_Ha
```

Regression models evaluated in the notebook include:

- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression

### 📊 Regression Evaluation

The models are evaluated using:

- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error
- R² — Coefficient of Determination

### 🏆 Current Regression Result

Based on the executed notebook results:

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Gradient Boosting | 0.6957 | 2.1188 | **0.9709** |
| Random Forest | 0.7137 | 2.5716 | 0.9571 |
| Linear Regression | 1.9561 | 4.9554 | 0.8408 |

**Best observed regression model:** Gradient Boosting

The notebook also performs prediction-error analysis, cross-validation, model comparison, and feature-importance analysis.

---

## 🏷️ Performance Classification

The notebook extends the analysis by grouping agricultural records into:

- **Low Performance**
- **Medium Performance**
- **High Performance**

The categories are created from the observed yield distribution.

Classification evaluation uses suitable metrics including:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Feature-importance analysis is also used to identify variables that are useful for agricultural performance classification.

---

## 📈 Agriculture Performance Dashboard

A final notebook-based **Agriculture Performance Dashboard** provides a visual summary of the major results.

### Dashboard Highlights

- Total Farms
- Average Yield
- Average Profit
- Average Revenue
- Water Efficiency
- Disease/Pest Risk
- Season-wise Yield
- Season-wise Profit
- Crop × Season Performance
- State Performance
- Water Usage vs Yield
- Disease/Pest Risk by Season
- Machine Learning Performance

### Dashboard Filters

The dashboard supports filtering by:

- Season
- Crop
- State
- Irrigation Method

The dashboard is implemented as a presentation layer on top of the existing analysis and Machine Learning results.

---

## 🔄 Project Workflow

```text
1. Imports & Project Setup
        ↓
2. Dataset Loading
        ↓
3. Dataset Understanding & Initial Inspection
        ↓
4. Data Structure & Information
        ↓
5. Statistical Summary
        ↓
6. Data Cleaning & Preprocessing
        ↓
7. Exploratory Data Analysis (EDA)
        ↓
8. Statistical Analysis & Hypothesis Testing
        ↓
9. Feature Engineering & Analytical Metrics
        ↓
10. Machine Learning — Yield Prediction
        ↓
11. Machine Learning — Performance Classification
        ↓
12. Model Evaluation & Feature Importance
        ↓
13. Data-Driven Insights & Recommendations
        ↓
14. Agriculture Performance Dashboard
        ↓
15. Final Project Summary & Conclusion
```

---

## 🛠️ Tools & Technologies

### Data Analytics
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

### Machine Learning
- Scikit-learn

### Model / Output Support
- Joblib
- OpenPyXL

### Development
- Jupyter Notebook
- Google Colab compatible workflow

---

## 📁 Project Structure

A recommended repository structure is:

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── VOIS_Major_Project_Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── README.md
│
├── Major Project_Seasonal Agriculture Performance Analysis.pdf
├── N.V.Yasasvi_VOIS_Major_Project_Seasonal_Agriculture_Performance_Analysis_PPT_Submission.pptx
│
├── agriculture_project_outputs/
│   ├── cleaned_agriculture_dataset.csv
│   ├── season_performance.csv
│   ├── state_performance.csv
│   ├── district_performance.csv
│   ├── crop_season_summary.csv
│   ├── regression_model_comparison.csv
│   ├── classification_model_comparison.csv
│   ├── yield_feature_importance.csv
│   ├── classification_feature_importance.csv
│   ├── best_yield_prediction_model.pkl
│   ├── best_performance_classifier.pkl
│   └── Seasonal_Agriculture_Performance_Analysis.xlsx
│
└── Screenshot Results/
    │
    ├── Data_Analytics/
    │   ├── 15. Average Yield by Season.png
    │   ├── 16. Profit by Season.png
    │   ├── 17. Revenue vs Cost by Season.png
    │   ├── 18. Rainfall by Season.png
    │   ├── 19. Temperature by Season.png
    │   ├── 20. Humidity by Season.png
    │   ├── 21. Water Usage by Season.png
    │   ├── 22. Water Efficiency by Season.png
    │   ├── 23. Disease and Pest Risk by Season.png
    │   ├── 24. Irrigation Method.png
    │   ├── 25. Crop Distribution.png
    │   ├── 27. Top Performing Crops by Yield.png
    │   ├── 29. Heatmap Crop vs Season.png
    │   ├── 33. Correlation Matrix.png
    │   ├── 34. Rainfall vs Yield.png
    │   ├── 35. Temperature vs Yield.png
    │   ├── 36. Seed Quality vs Yield.png
    │   ├── 37. Fertilizer vs Yield.png
    │   ├── 38. Soil Moisture vs Yield.png
    │   ├── 39. Profit vs Yield.png
    │   ├── 40. Water Efficiency vs Yield.png
    │   ├── 41. Box Plot - Yield by Season.png
    │   ├── 42. Box Plot - Profit by Season.png
    │   ├── 52. Most Profitable Crops.png
    │   ├── 54. Irrigation Method vs Water...png
    │   ├── 56. Seasonal Resource Usage...png
    │   └── 58. Profit Margin by Season.png
    │
    ├── Machine_Learning/
    │   ├── 73. Model Comparison Visualization.png
    │   ├── 74. Actual vs Predicted Yield.png
    │   ├── 76. Top 15 Important Features.png
    │   ├── 91. Top Performing Regions.png
    │   ├── 93. Disease and Pest Risk vs Yield.png
    │   └── 106. Machine Learning Dashboard.png
    │
    └── Dashboard/
        ├── 104. Agriculture Performance Dashboard.png
        └── 105. Interactive Dashboard.png
```

---

## ▶️ How to Run the Project

### 1. Clone or download the repository

Place the notebook and dataset in the same project folder.

### 2. Install the required packages

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn openpyxl joblib
```

### 3. Open the notebook

Open:

```text
VOIS_Major_Project_Seasonal_Agriculture_Performance_Analysis.ipynb
```

using Jupyter Notebook, JupyterLab, or Google Colab.

### 4. Ensure the dataset is available

The notebook expects:

```text
seasonal_agriculture_performance_dataset.csv
```

### 5. Run the notebook from top to bottom

Execute the cells in order so that the cleaning, analysis, Machine Learning, dashboard, and final reporting sections use the prepared results.

---

## 📌 Key Analytical Areas

The project investigates:

| Area | Analysis |
|---|---|
| Season | Yield, profit, production, water, risk |
| Crop | Yield and profitability |
| State | Agricultural performance |
| District | Regional performance |
| Environment | Rainfall, temperature, humidity, sunlight |
| Soil | pH and moisture |
| Nutrients | Nitrogen, phosphorus, potassium |
| Farming Inputs | Fertilizer, pesticide, seed quality |
| Irrigation | Yield, water use, water efficiency |
| Risk | Disease and pest risk |
| Economics | Revenue, cost, profit |
| Statistics | Correlation, ANOVA, outliers |
| Machine Learning | Yield prediction and performance classification |
| Dashboard | KPI and result visualization |

---

## 💡 Insights & Recommendations

The notebook generates data-driven insights from the actual dataset, including:

- Seasonal performance differences
- Strong and weak crop-season combinations
- Regional performance variation
- Environmental relationships
- Resource-use patterns
- Water-efficiency differences
- Disease/pest risk variation
- Economic performance differences
- Factors useful for yield prediction
- Machine Learning performance
- Areas requiring further investigation

Recommendations are based on observed patterns in the dataset and are intended as analytical decision support rather than direct agricultural prescriptions.

---

## ⚠️ Important Note on Findings

Specific seasonal, crop, regional, and risk conclusions should be taken from the **executed notebook outputs**.

The project does not assume that one season, crop, or irrigation method is always best. Findings should be interpreted from the calculated tables, visualizations, statistical tests, and Machine Learning results.

---

## 🎯 Overall Outcome

The project combines:

**Data Analytics + Machine Learning + Dashboard Visualization**

The **Data Analytics component** provides the core seasonal agricultural analysis.

The **Machine Learning component** adds predictive and classification capabilities.

The **Dashboard component** brings the major results together into an accessible visual summary.

Together, these components provide a structured, evidence-based understanding of seasonal agricultural performance.

---

## ✅ Project Status

- ✅ Dataset understanding
- ✅ Data cleaning and preprocessing
- ✅ Exploratory Data Analysis
- ✅ Seasonal analysis
- ✅ Crop and regional analysis
- ✅ Statistical analysis
- ✅ Visualization
- ✅ Feature engineering
- ✅ Yield prediction
- ✅ Performance classification
- ✅ Model evaluation
- ✅ Feature importance
- ✅ Data-driven insights
- ✅ Recommendations
- ✅ Agriculture Performance Dashboard
- ✅ Final summary and conclusion

---

## 📝 Conclusion

The **Seasonal Agriculture Performance Analysis** project demonstrates how agricultural data can be transformed into meaningful insights through a structured Data Analytics workflow.

The project further extends the analysis with Machine Learning for yield prediction and performance classification, while the dashboard provides a concise visual presentation of important analytical and predictive results.

The final conclusions and recommendations are based on the available dataset and should be validated with appropriate agricultural knowledge and field-level evidence before practical implementation.

---

## 👤 Academic Context

**Major Project:** Seasonal Agriculture Performance Analysis  
**Program Context:** VOIS AICTE Batch1 2026–2027  
**Project Focus:** Data Analytics with Machine Learning and Dashboard Enhancements

---

### ⭐ Project Theme

> **Understand seasonal agricultural performance through data, analytics, prediction, and visualization.**
