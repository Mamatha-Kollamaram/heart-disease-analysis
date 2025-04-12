# Uncovering Clinical Insights into Heart Disease Risk

This project performs **Exploratory Data Analysis (EDA)** on heart disease data from Cleveland and Hungary, identifying key patterns and statistical relationships between clinical features and heart disease presence.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Features](#dataset-features)
- [Technologies Used](#-technologies-used)
- [Key Findings](#key-findings)
- [How to Run](#how-to-run)
- [Dataset](#dataset)
- [Results](#results)
- [Author](#author)
- [License](#license)


## Project Overview

| Aspect               | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Data Cleaning**    | Handling missing values, data type conversion, and feature engineering      |
| **EDA**              | 15+ visualizations including histograms, box plots, and correlation matrices|
| **Statistical Tests**| T-tests and Chi-Square tests for regional/disease comparisons               |
| **Key Insights**     | Identified top risk factors and regional variations                         |

## Dataset Features

| Feature               | Description                                  | Type        |
|-----------------------|----------------------------------------------|-------------|
| `age`                 | Patient age in years                         | Continuous  |
| `sex`                 | Gender (1=male, 0=female)                   | Categorical |
| `chest_pain_type`     | Type of chest pain (4 categories)            | Categorical |
| `resting_bp`          | Resting blood pressure (mm Hg)               | Continuous  |
| `cholesterol`         | Serum cholesterol (mg/dl)                    | Continuous  |
| `max_heart_rate`      | Peak exercise heart rate                     | Continuous  |
| `exercise_angina`     | Exercise-induced angina (1=yes, 0=no)        | Categorical |
| `target`              | Heart disease presence (1=yes, 0=no)         | Binary      |

*Complete feature list available in the notebook*

## 🛠 Technologies Used

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-blue?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-blue?logo=seaborn)

**Core Libraries:**
- Pandas (Data manipulation)
- NumPy (Numerical computing)
- Matplotlib/Seaborn (Visualization)
- SciPy (Statistical testing)

## Key Findings
**Strongest Predictors:**

- **Positive correlation**: `exercise_angina`, `st_depression`  
- **Negative correlation**: `max_heart_rate`, `st_slope`

**Regional Differences:**

-Cleveland patients had higher average cholesterol (p < 0.05)
-Hungarian patients showed more exercise-induced angina

**Risk Factors:**

-Patients with heart disease had significantly higher ST depression (p < 0.01)
-Males showed 2.3x higher disease prevalence


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-eda.git ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt ```
3. Run the Jupyter notebook or Python script:
   ```bash
   jupyter notebook heart_disease_eda.ipynb ```

## Dataset
This project uses the UCI Heart Disease Dataset, available at UCI Machine Learning Repository.

-Link: [Visit the UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
-Multiple sources in one file (e.g., Cleveland, Hungarian, Switzerland, Long Beach)
-Raw and less pre-cleaned → ideal to showcase your data cleaning skills
-Real clinical values, providing authentic and challenging insights
-You can focus on a single hospital source (like Cleveland) or compare multiple for a unique perspective

## Results
- Visualizations such as histograms, count plots, and pair plots are included to help you understand the data better.

- Statistical analysis reveals significant relationships between different features and heart disease presence.

## Author
**Kollamaram Mamatha**
[LinkedIn: Mamatha Kollamaram](https://www.linkedin.com/in/MamathaKollamaram/)

## License

This project is licensed under the MIT License.

Copyright (c) 2025 Kollamaram Mamatha
