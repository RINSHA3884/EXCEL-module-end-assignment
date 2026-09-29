# EXCEL-module-end-assignment# Healthcare Data Analysis

## Project Overview

This project focuses on cleaning, transforming, analyzing, and visualizing healthcare-related data using Microsoft Excel. The analysis was performed to identify patterns and relationships among patient demographics, health conditions, medical history, hospital information, and healthcare charges.

## Objectives

* Clean and prepare the healthcare dataset for analysis.
* Handle missing and inconsistent data.
* Transform and categorize relevant data fields.
* Use Excel formulas and functions for data preparation.
* Create PivotTables and PivotCharts for analysis.
* Analyze relationships between different healthcare variables.
* Create an interactive dashboard using slicers.

## Data Cleaning and Preparation

The following data-cleaning and transformation tasks were performed:

* Used **VLOOKUP** to combine required information from different tables.
* Split the Customer Name column into **Title, First Name, and Last Name** using **Text to Columns**.
* Handled missing categorical values using the most frequently occurring value.
* Replaced missing **State ID** values with **Unknown** using Find and Replace.
* Replaced **No major surgery** with **0** in the Number of Major Surgeries column.
* Checked the **Heart Issues** and **Smoker** columns for inconsistencies and standardized the entries.
* Created a **Weight Status** column using a nested **IF function** based on BMI categories.
* Combined Year, Month, and Date into a **Date of Birth** column using the **DATE function**.
* Applied the required **DD/MMM/YYYY** date format.

## Analysis Performed

### 1. Cancer History and Smoking Status

Analyzed the distribution of cancer history among smokers and non-smokers using a PivotTable and a pie/donut chart.

### 2. Hospital Tier and Healthcare Charges

Compared average healthcare charges across different hospital tiers using a PivotTable and clustered column chart.

### 3. Transplant History, Major Surgeries and HbA1c

Compared the total number of major surgeries and average HbA1c between patients with and without a history of transplant.

### 4. Weight Status and Diabetes Status

Analyzed how average healthcare charges vary across different weight-status and diabetic-status categories.

### 5. Hospital Tier Across States

Compared the average healthcare charges for different hospital tiers within different states.

### 6. Age and BMI

Used a scatter plot and linear trendline to examine the relationship between Age and BMI.

### 7. Age and HbA1c

Used a scatter plot and linear trendline to examine the relationship between Age and HbA1c.

### 8. Age and Healthcare Charges

Created a PivotTable and line chart to explore the relationship between Age and average healthcare charges.

## Excel Techniques Used

* VLOOKUP
* IF / Nested IF
* DATE
* Find and Replace
* Text to Columns
* PivotTables
* PivotCharts
* Scatter Plots
* Linear Trendlines
* Pie/Donut Charts
* Clustered Column Charts
* Line Charts
* Slicers

## Dashboard

An interactive dashboard was created using Excel PivotCharts and slicers. Slicers for **Weight Status** and **Diabetic Status** were added to allow users to filter and compare healthcare outcomes and charges.

## Files Included

* **Excel file:** Contains the cleaned dataset, analysis, PivotTables, PivotCharts, and dashboard.
* **Word file:** Contains the questions, methodology, and answers for the assignment.

## Tools Used

* Microsoft Excel
* Microsoft Word
* GitHub

## Conclusion

This project demonstrates the use of Excel for healthcare data cleaning, transformation, analysis, and visualization. The use of formulas, PivotTables, charts, and interactive slicers helped organize the data and identify relationships between patient characteristics, medical history, and healthcare charges.
