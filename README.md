 Overview

This Databricks notebook performs an exploratory data analysis (EDA) on a healthcare appointment dataset. The goal is to understand patient behaviors, uncover trends related to no-shows, and evaluate health conditions such as hypertension, diabetes, and alcoholism.
📂 Key Features

    Data ingestion and cleaning

    Feature engineering (e.g., creating age groups, computing show/no-show rates)

    Analysis of patient demographics

    Correlation of appointment adherence with medical conditions

    Time-series analysis of appointment trends

🔧 Technologies Used

    Databricks (Spark environment)

    Python with libraries: pandas, matplotlib, seaborn, numpy

📊 Analysis Focus Areas

    Appointment no-show distribution by age and gender

    Health condition distributions (Diabetes, Hypertension, Alcoholism)

    Time-based appointment patterns (monthly trends)

    Derived features like age_group and show_count for enhanced visualization

📁 How to Run

    Upload the dataset to Databricks FileStore or mount a location.

    Run each cell in order.

    Ensure required Python libraries are installed (%pip install pandas matplotlib seaborn if needed).

    Use the output for dashboard visualizations.

📌 Output

The final output is a cleaned dataset and multiple visualizations, which are intended for export or integration with BI tools like Power BI or Databricks dashboards.
