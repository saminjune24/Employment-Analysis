# Macroeconomic Labor Analysis: Employment & Wage Dynamics (2006-2023)

## 📌 The Business Problem
Understanding how macroeconomic shocks impact the labor market is critical for workforce planning and corporate strategy. This project evaluates the resilience of various industries during major economic events, including the 2008 financial crisis and the COVID-19 pandemic, by tracking job creation, workforce retention, and average weekly earnings.

## 📊 Data Architecture & Sourcing
* **Data Source:** U.S. Bureau of Labor Statistics (BLS) Current Employment Statistics (CES) program.
* **Scope & Dimensions:** Tracks historical trends spanning 17 years (2006–2023). The population represents nonfarm wage and salary workers across the U.S., derived from over 144,000 businesses and government agencies representing approximately 697,000 worksites.
* **Key Metrics Analyzed:** * Aggregate Weekly Hours of All Employees (in thousands)
  * Average Weekly Earnings of Production and Nonsupervisory Employees (adjusted to 1982-84 dollars)
  * Industry Classifications (e.g., Aerospace, Wood product manufacturing, Healthcare, Technology)

## 🛠️ Analytical Methodology
* **Data Engineering:** Merged multiple CES data files via industry and data type codes. Addressed structural data issues by dropping missing records, formatting time-series date columns, and aggregating industries into broader comparative sectors.
* **Outlier Detection:** Implemented the Interquartile Range (IQR) method to ensure extreme temporary workforce fluctuations did not skew longitudinal trends.
* **Exploratory Data Analysis (EDA):** Built visual comparative analyses across sectors to identify distinct adaptation strategies—comparing industries that scaled volume against those that restricted headcount while increasing wages.
* **Tech Stack:** Python (Pandas, NumPy, Matplotlib/Seaborn), Jupyter Notebook.

## 🚀 Key Strategic Insights
* **Sector Resilience:** The healthcare and technology sectors demonstrated structural resilience, sustaining growth during broader economic downturns.
* **Wage vs. Volume Dynamics:** Analysis revealed a post-pandemic shift toward specialized, higher-paying roles; wages continued to rise across multiple sectors even during periods of heavy job contraction, indicating a strategic shift from labor volume to labor productivity.
