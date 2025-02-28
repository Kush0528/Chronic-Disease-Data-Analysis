# Chronic-Disease-Data-Analysis
## Project Overview

 This Analysis aims to examine trends in chronic diseases throughout the United States using the U.S. Chronic Disease Indicators dataset. Finding regional and demographic differences in the prevalence of chronic diseases including diabetes, cardiovascular disease, and asthma is the main goal of the investigation.

## Data source & Description
Data Source - CDC’s Centers for Disease Control and Prevention portal (https://data.cdc.gov/Chronic-Disease-Indicators/U-S-Chronic-Disease-Indicators/hksd-2xuw/about_data)  
Data type - Structured, CSV file  
Key Statistics - 309,216 Rows & 34 Columns

## Preprocessing Steps
### 1) Data Cleaning:
Dropped columns that have no values at all. Numeric columns were filled with their median values. In categorical columns, "Unknown" was used for filling data.
### 2) Data Aggregation:
To concentrate on state-specific trends, national-level entries were eliminated. For thorough statistical summaries, data was grouped by year, state, and disease type.

## Analysis
### 1) Trend Analysis - 
![Image](https://github.com/user-attachments/assets/fe99cfe9-a868-440a-862a-a5ddc43ba690)
![Image](https://github.com/user-attachments/assets/8140a798-3467-4574-b0c8-cd1cbe52afb2)        
Assessed patterns in the mortality rates from diabetes and asthma. Matplotlib-created line plots that showed patterns over time were used to visualize this.
### 2) Comparative Analysis -
![Image](https://github.com/user-attachments/assets/5f4b644e-71d7-4809-b1ab-760bceb8f891)
The prevalence of cardiovascular disease by gender was compared by state using bar plots.
### 3) Geospatial Analysis -
![Image](https://github.com/user-attachments/assets/6c743f2d-32a2-4762-9b00-04bf753bfa82)
Mapped alcohol-related mortality rates across the United States.

## Libraries Used
1) Pandas - For data loading, cleaning, aggregation, and manipulation.
2) Matplotlib - For creating static visualizations, such as line and bar plots.
3) Cartopy - For geospatial mapping.
4) Dash - For building the interactive dashboard.
5) Ipython.display - To render rich HTML content, such as styled Data frames tables. 

## Interactive Dashboard
![Image](https://github.com/user-attachments/assets/25a4ff4b-4063-4ec6-b2fe-e06ef735b422)
Dash was used to create a dynamic dashboard with interactive visuals that let users investigate "Binge Drinking Prevalence Among Adults." The interface included a drop-down menu for choosing states, and line charts that updated dynamically to show patterns over time. The project's objective of giving stakeholders the ability to interactively study data was perfectly embodied by the Dash application.

## Conclusion
The Analysis recommends focusing on gender-specific health policies and implementing targeted public health initiatives in high-mortality areas. Reaching out to high-risk individuals and closely monitoring changes in chronic conditions can help prevent future health disasters.
