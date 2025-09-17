# Bellabeat: Daily Activity Data Analysis

## Project Overview
This project is a case study analyzing smart device usage data to help inform the marketing strategy for Bellabeat, a high-tech company that creates health-focused products for women. As a junior data analyst on the marketing team, the goal was to identify trends in smart device usage and apply those insights to one of Bellabeat's products to find new growth opportunities.  
The analysis follows the steps of the data analysis process: ask, prepare, process, analyze, share, and act.  

## Business Task
Analyze consumer usage data from non-Bellabeat smart devices to discover trends and apply those insights to one of Bellabeat's products, with the goal of providing high-level recommendations for the company's marketing strategy.  

## Data Source
The data used for this analysis is the FitBit Fitness Tracker Data from Kaggle. This public dataset was collected from 30 FitBit users who consented to sharing their personal tracker data, including daily activity, steps, calories burned, heart rate, and sleep records.  

Limitations: The dataset has a small sample size of only 30 users and was collected in 2016, which may introduce potential bias and affect the analysis and recommendations.  

## Tools
• R: The entire analysis, including data processing, cleaning, and visualization, was performed using R.  

• RStudio: The integrated development environment used for the project.

• Tidyverse: A collection of R packages used for data manipulation and visualization.  

## Key Steps & Processes
### 1. Data Preparation and Cleaning
• The raw data, which was stored in multiple CSV files, was combined into a single dataframe.  

• The ActivityDate column was converted to a proper date format.  

• Duplicate entries were removed from the combined dataset.  

• No missing values were found in the dataset after checking for nulls.  
### 2. Analysis and Visualizations
• Average Activity Levels: A summary of average time spent in different activity levels (very active, fairly active, lightly active, and sedentary) was calculated and visualized. The results showed that users spend a significant amount of time in sedentary minutes (993 minutes) and lightly active minutes (185 minutes), with much less time in very active (19.7 minutes) and fairly active (13.4 minutes) minutes.  

• Total Steps vs. Calories Burned: A scatter plot was created to explore the relationship between total steps and calories burned. The visualization shows a positive correlation, indicating that as the number of total steps increases, the calories burned also tend to increase.  

• Total Distance vs. Calories Burned: A similar scatter plot was created to analyze the relationship between total distance and calories burned. This visualization also shows a clear positive correlation.  

## Next Steps
• Further Analysis: While this project focused on daily activity, future analysis could expand to include other available datasets, such as sleep records and heart rate data, to gain a more comprehensive understanding of user habits.  

• Product Recommendations: Based on these findings, the next phase would involve developing specific, high-level marketing recommendations for a Bellabeat product, such as the Bellabeat app or one of its trackers, like the Leaf or Time, to help the company grow.
