# NutriRisk Analytics: Food Nutrition & Health Risk Intelligence

An end-to-end data analytics project that analyzes food nutrition patterns and predicts potential health risks such as **diabetes, obesity, and heart disease** using nutrient-based analysis.

---

## Project Overview

This project uses the **USDA Foundation Foods Dataset** to analyze nutritional composition and identify foods that may contribute to health risks based on nutrient patterns.

The system transforms raw nutritional data into meaningful health insights through:

- Data preprocessing
- Nutritional analysis
- Health risk scoring
- SQL-based data storage
- Interactive Power BI dashboards

The goal is to make food nutrition data easier to understand and support healthier food choices through analytics.

---

## Problem Statement

People often consume foods without understanding their nutritional impact on long-term health. This project aims to analyze food nutrients and identify potential risk factors associated with:

- Diabetes
- Obesity
- Heart Disease

By studying nutrient composition such as sugar, calories, sodium, fat, cholesterol, fiber, and protein, the project generates meaningful risk insights.

---

## Project Workflow & Architecture

![Project Workflow & Architecture](design/architecture.png)

---

## Simple Project Flow

```text
USDA Dataset
      ↓
Data Cleaning & Preprocessing
      ↓
Data Merging & Transformation
      ↓
Health Risk Scoring
(Diabetes | Obesity | Heart Disease)
      ↓
Exploratory Data Analysis (EDA)
      ↓
SQL Database
      ↓
Power BI Dashboard
      ↓
Health Insights
```

---

## Dataset Information

### Primary Dataset
**USDA Foundation Foods Dataset**

Files Used:
- `food.csv`
- `food_nutrient.csv`
- `nutrient.csv`
- `food_category.csv`

### Future Scope (Planned Integration)
- Diabetes Dataset
- Obesity Dataset
- Cardiovascular Disease Dataset

---

## Tech Stack

### Programming & Analysis
- Python
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn
- Power BI

### Database
- SQL

---

## Planned Features

### Data Preprocessing
- Handle missing values
- Merge USDA food tables
- Create master nutrition dataset

### Health Risk Scoring
- Diabetes Risk Score
- Obesity Risk Score
- Heart Disease Risk Score

### Exploratory Data Analysis
- Nutrient distributions
- Food category analysis
- Correlation analysis
- High-risk food identification

### Dashboard
- Nutrition insights
- High-risk foods
- Disease risk visualization
- Nutrient comparison

---

## Project Structure

```text
food-health-risk-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── sql/
│
├── powerbi/
│
├── reports/
│
├── design/
│   └── architecture.png
│
├── README.md
└── requirements.txt
```

---

## Current Status

🚧 Project in Development (Phase 1)

- [x] Dataset Collection  
- [x] Workflow & Architecture Design  
- [ ] Data Understanding  
- [ ] Data Cleaning  
- [ ] Feature Engineering  
- [ ] Exploratory Data Analysis  
- [ ] SQL Integration  
- [ ] Power BI Dashboard  

---

## Future Improvements

- Real healthcare dataset integration
- Advanced health risk prediction
- Machine learning-based food risk classification
- Personalized food recommendations

---

## Author

Built as a data analytics portfolio project focusing on **nutrition, healthcare, and biological data analysis**.