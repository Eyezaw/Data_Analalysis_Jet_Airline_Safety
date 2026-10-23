# Aviation Accident Data Analysis

## 📝 Project Overview

This repository contains a data analysis project focused on aviation accident data to derive actionable safety recommendations for an airline and airplane insurer. The analysis explores accident data from 1948-2023, filtering for professionally built aircraft that could still be active.

The primary goals of this analysis are to:
1.  Identify aircraft makes and models that exhibit **low rates of total destruction** and **low likelihood of fatal or serious passenger injuries**.
2.  Provide separate recommendations for **small vs. large passenger aircraft**.
3.  Analyze and discuss at least two general factors (e.g., weather, phase of flight) that contribute to the severity of an accident.

All claims are supported by statistical evidence and visualizations to ensure they are robust and reliable.

## 📂 Repository Contents

This project is contained within two Jupyter Notebooks to reflect a clean, modular workflow:

*   `Aviation_Accidents_Cleaning.ipynb`:
    *   This notebook focuses on the **data loading, inspection, and cleaning** process.
    *   It handles filtering the data by date, aircraft category, and build type as requested by the client.
    *   It includes the creation of key derived metrics for analysis, such as the **`Fatal.Serious.Fraction`** (the proportion of occupants fatally or seriously injured) and a binary **`Aircraft.Destroyed`** indicator.
    *   The final cleaned dataset is saved to `cleaned_aviation_data.csv`.

*   `Aviation_Accidents_Data_Analysis.ipynb`:
    *   This notebook loads the cleaned data and performs **exploratory data analysis (EDA)**.
    *   It visualizes safety metrics (injury rates and destruction rates) across different aircraft makes and models.
    *   It investigates the relationship between accident outcomes and factors like **Weather Condition** and **Phase of Flight**.
    *   The notebook concludes with data-driven recommendations and a discussion of the findings.

*   `AviationData.csv`:
    *   This is the original, raw dataset used for the analysis.

## 📊 Libraries Used

This project was developed using Python and the following core data science libraries:

*   **Pandas:** For data loading, cleaning, transformation, and aggregation.
*   **NumPy:** For efficient numerical operations.
*   **Matplotlib:** For creating static, animated, and interactive visualizations.
*   **Seaborn:** For building on Matplotlib to create more attractive and informative statistical graphics.

## 🚀 How to Use This Repository

To run and explore this analysis locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Eyezaw/Data_Analalysis_Jet_Airline_Safety/edit/main/README.md
