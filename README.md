# Employment-Analysis
EDA for Analyzing Employment and Wages Across Different Industries
Analyzing Employment and Wages Across Different Industries
Samin Bahizad
June 5
Introduction
For this project, I wanted to better understand how employment and wages have shifted across different industries in the U.S. over time. I focused on data from the U.S. Bureau of Labor Statistics (BLS) because it provides detailed monthly statistics on employment, unemployment, and earnings by industry. The data is extensive and captures historical trends from 2006 to 2023, which allows me to explore how major economic events like the 2008 recession and the COVID-19 pandemic impacted different sectors.

What drew me to this dataset is that employment trends often reflect the broader health of the economy. I was curious to see which industries showed growth, which struggled, and how workers' earnings evolved across different time periods. My goal was to track not just how many people were working, but also whether their pay changed — and how that varied by industry.

The three main fields I focused on were:

Industry sector — to see which areas of the economy were driving job creation.
Employment numbers — to understand how job counts changed over time.
Average weekly earnings — to evaluate whether workers’ wages were rising or stagnating.
My hypothesis was that healthcare and tech-related industries would show stronger resilience and consistent growth, while sectors like retail or manufacturing might be more sensitive to economic disruptions. I also wanted to understand whether some industries recovered faster than others after major downturns.

The population represented by this data includes nonfarm wage and salary workers across the U.S., with data collected from over 144,000 businesses and government agencies, representing around 697,000 worksites. While it’s not a full census, the CES program uses stratified sampling and weighting to ensure it captures national labor market trends accurately.

For this analysis, I used the full dataset across industry, wage, and employment dimensions. After merging and cleaning the data into a readable format, I explored trends from 2006 through 2023 to gain insight into how different parts of the job market evolved and what that says about the broader economy.

Data Explained
Data Source
The data comes from the Bureau of Labor Statistics CES. It includes employment and earnings data across various industries from 2006 to 2023.

Data Preparation
To get the dataset ready for analysis, I did the following:

Merged multiple CES data files using industry and data type codes.
Dropped unnecessary columns with mostly missing values.
Checked and removed duplicate rows (none were found).
Identified and removed outliers using the IQR method.
Converted the value column to numeric format.
Made sure there were no missing values in important columns.
Created a proper date column from year and month for time-based analysis.
Removed industries with missing records
Added a 'Sector' column to group industries for comparative analysis
