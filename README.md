# Lifestyle Health Analysis with Python (BMI, Risk Scoring & Visual Insights)

This project explores how daily lifestyle habits such as **sleep**, **water intake**, **diet**, **stress**, **smoking**, and **physical activity** affect a person's health—especially their **Body Mass Index (BMI)** and risk levels. The goal is to uncover hidden patterns and segment individuals into health categories using exploratory data analysis, feature engineering, and scoring logic.

---

##  Dataset Used

**Source**: Kaggle – Healthy Lifestyle and Body Indicators (Synthetic)

- 13 Columns | 7500 Rows  
- Features include: `SleepHours`, `WaterIntake`, `BMI`, `SmokingStatus`, `StressLevel`, `PhysicalActivity`, `DietQuality`, etc.

---

##  Project Objectives

- Analyze the impact of lifestyle choices on **BMI**
- Segment users by gender, age group, and lifestyle habits
- Create a **Lifestyle Risk Score** using conditional logic
- Generate a **Final Risk Category** (Low / Moderate / High)
- Provide **data-driven health insights** for preventive care

---

##  Key Techniques Used

- **Python Libraries**: pandas, seaborn, matplotlib, numpy
- **EDA**: missing value analysis, distribution plots, heatmaps, pairplots
- **Feature Engineering**:
  - Stress Category (Low / Medium / High)
  - Lifestyle Score using combined habits
  - Risk Classification
- **Visualizations**: Correlation heatmaps, BMI trends, multivariate scatter plots
- **Plot Saving**: All charts saved under `/images` for reuse

---

##  Visual Summary Report

Includes 10+ saved charts with insights such as:

- BMI vs Sleep Hours
- BMI vs Water Intake
- Physical Activity vs BMI
- Stress Level Distribution
- Lifestyle Score vs Risk
- Final Risk Category by Gender

---

##  Key Insights

- Poor diet, low activity, and low water intake strongly relate to **higher BMI**
- High stress levels correlate with unhealthy habits and **higher risk scores**
- Multivariate analysis reveals clusters of high-risk individuals based on lifestyle mix
- Sleep imbalance (too low or too high) also links to BMI spikes

---
##  What I Learned
- How lifestyle variables impact BMI and health outcomes
- Risk classification using business logic, not ML
- Translating messy health behavior data into visual insights


##  Folder Structure
lifestyle_health_analysis/
├── lifestyle_health_analysis.ipynb # Jupyter Notebook with code & plots
├── visual_summary_report.pdf # Visual PDF for quick review
└── README.md # This file
