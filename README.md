# 🎬 Netflix Data Analysis (Refactored)

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📄 Overview

This project is a **comprehensive refactoring** of an exploratory data analysis on the Netflix dataset. 
While the initial analysis provided basic insights, this version implements **advanced data cleaning techniques**, robust feature engineering, and professional-grade visualizations to derive clearer business insights.

## 🚀 Key Improvements & Features

* **Robust Data Cleaning:** Implemented a strategy to handle missing values (imputation for categorical data, removal for critical metadata) instead of generic filling.
* **Advanced Parsing:** Correctly handled multi-country productions (splitting strings) to avoid skewed geographical statistics.
* **Time-Series Analysis:** Converted raw dates into datetime objects to track content growth accurately.
* **Professional Visualization:** Used a custom color palette compliant with Netflix's brand identity.

## 📊 Insights Summary

1.  **Content Strategy:** Movies still dominate the platform (~70%), but TV Show production has seen a sharper increase in recent years.
2.  **Geographical Reach:** While the USA leads, there is a significant and growing contribution from India and the UK.
3.  **Content Duration:** The "Golden Standard" for movies on the platform sits firmly between 90 and 100 minutes.

## 🛠️ How to Run

1.  Clone the repository:
    ```bash
    git clone [https://github.com/ArmelKI/Netflix-Analysis-Refactored.git](https://github.com/ArmelKI/Netflix_data_analysis_V2.git)
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook notebooks/netflix_analysis.ipynb
    ```

## 👤 Author

**Armel Stéphane Novak KI** *Engineering Student @ Télécom Nancy | Data Science Enthusiast*

---
*Data Source: Kaggle*