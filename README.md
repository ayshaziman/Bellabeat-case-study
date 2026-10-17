# Bellabeat Fitness Tracker Analysis

## Project Overview

This case study analyzes Fitbit fitness tracker data to identify patterns in users' daily activity and sleep habits. The findings can help Bellabeat understand user behavior and develop data-informed marketing strategies.

## Business Task

Analyze smart-device usage data to understand activity and sleep patterns and provide recommendations for Bellabeat's marketing strategy.

## Tools Used

* Python
* Jupyter Notebook
* Pandas
* Tableau

## Dataset

The dataset comes from the Fitbit Fitness Tracker Data shared on Kaggle by Mobius. It contains activity and sleep records from Fitbit users collected in 2016.

## Data Cleaning

* Checked the datasets for missing values and duplicate rows.
* Converted activity and sleep date columns to datetime format.
* Removed 3 duplicate rows from the sleep dataset.
* Prepared cleaned daily activity and sleep datasets for analysis.

## Key Findings

* Users recorded an average of approximately 6,547 steps per day.
* Wednesday had the highest average daily steps, at approximately 7,511.
* Tuesday had the lowest average daily steps, at approximately 4,915.
* Users slept for an average of approximately 6.99 hours per day.
* Time asleep and time in bed showed a strong positive correlation of approximately 0.93.
* Daily steps and calories burned showed a moderate positive correlation of approximately 0.58.

## Visualizations

![Bellabeat Dashboard](Bellabeat Fitness Tracker Analysis.png)
A Tableau dashboard was created with two visualizations:

* Daily Steps Over Time
* Sleep Duration Over Time

## Recommendations

* Encourage users to monitor their daily steps and activity levels.
* Promote healthy sleep habits through Bellabeat's wellness features.
* Use these findings as initial insights while considering the dataset's small sample size and age.

## Limitations

The dataset contains records collected in 2016 from a limited group of Fitbit users. The findings may not represent all users or current behavior.

## Project Files

* `Bellabeat_Case_Study.ipynb` — Data preparation and analysis
* `daily_activity_clean.csv` — Cleaned daily activity data
* `sleep_day_clean.csv` — Cleaned sleep data
* `Bellabeat Case Study.twbx` — Tableau dashboard
