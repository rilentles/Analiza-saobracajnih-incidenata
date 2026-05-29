# Traffic-incident-analysis

# Overview

This project analyzes traffic incident data in Belgrade to identify temporal and geographic patterns. The goal is to understand when and where accidents are most likely to occur using data analysis and interactive visualizations.

# Tools & Technologies

* Python (pandas) – data cleaning and preprocessing
* Google Colab - Data enviorment for exploration
* Power BI – interactive dashboard and visualization, DAX  
* Parquet – cleaned dataset storage format

# Project Structure

notebooks/ → data cleaning 
data/ → raw and cleaned datasets
powerbi/ → Power BI dashboard file (.pbix)
images/ → dashboard screenshots

# Data Processing

The raw dataset was cleaned and transformed using Python:
* Removed unnecessary columns
* Split datetime into date and time components
* Filtered data for Belgrade only
* Created new features such as:
* Day of week
* Month
* Hour of incident
Final dataset was exported as a Parquet file for use in Power BI.

# Analysis Performed

Incident distribution by municipality
Hourly and daily accident patterns
Rush hour vs non-rush hour comparison
Geographic visualization using maps
Heatmap analysis of accident frequency

# Key Insights

*Incidents peak around 17:00 (evening rush hour)
*Certain municipalities show higher accident concentration
*Weekday traffic shows more variability than weekends
*Clear temporal patterns linked to commuting hours
*Thursday has the most incidents overall
