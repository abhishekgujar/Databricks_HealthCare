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

HealthCare_Dashboard

Overview

The HealthCare Dashboard presents interactive visualizations based on the analysis performed in the accompanying Databricks notebook. It highlights key insights into patient behavior, particularly appointment adherence across demographics and medical conditions.
📊 Key Dashboard Components

    Show Rate by Age Group

        Visualizes how appointment no-show rates vary across different age segments.

    Show Rate by Gender

        Compares missed appointments between male and female patients.

    Age Group vs Diabetes

        Displays the distribution of diabetic patients by age group.

    Age Group vs Hypertension

        Shows the count of hypertension cases across age categories.

    Monthly Show Trend

        Line chart tracking no-show rates month-wise to identify seasonal patterns.

    Appointment Trends Over Time

        Tracks total vs. attended appointments to highlight behavioral trends.

    Age Group vs Alcoholism

        Highlights alcoholism prevalence among age groups.

    Age Group vs Handicap

        Visualizes the distribution of handicapped patients across age groups.

    Built using Databricks Notebooks + Dashboard view

    Visualizations created using Databricks’ built-in charting and Python libraries

📌 Usage

Ideal for healthcare analysts or hospital administrators to identify patterns in patient behavior and optimize scheduling, reminders, or follow-up procedures.
