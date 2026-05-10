# Weather Data Analysis — AI/ML Foundations Assignment

## Overview
Exploratory data analysis and Python data handling project using a real-world 
weather dataset containing 96,453 hourly recordings from 2006 to 2016.

## Assignments Completed
- **Assignment 1** — Understanding Data and Statistics
- **Assignment 2** — Python for Data Analysis

## Dataset
- **Source:** Kaggle — Weather History Dataset
- **Original size:** 96,453 rows, 12 columns
- **Cleaned size:** 96,429 rows, 15 columns

## What Was Done
- Loaded and inspected raw weather data using Pandas
- Identified and handled 517 missing values in Precip Type column
- Removed 24 duplicate rows
- Converted date column to datetime format
- Created new calculated columns — Temperature (F), Month, Year
- Performed group-by, filtering, sorting and correlation analysis
- Generated statistical summaries — mean, median, mode, std, quartiles
- Created visualisations — histogram, box plot, scatter plot, correlation heatmap

## Key Findings
- Temperature and Humidity are strongly negatively correlated (-0.63)
- July is the hottest month averaging 22.97°C — January coldest at 0.82°C
- Wind speed contains 1,562 storm events above 30 km/h
- Pressure behaves independently of all other weather variables

## Files in This Repository
| File | Description |
|------|-------------|
| weatherHistory.csv | Original raw dataset |
| weatherHistory_cleaned.csv | Cleaned dataset after preprocessing |
| weather_dataset.py | Python analysis script |
| Weather Pattern Analysis.pdf | Assignment 1 report |
| Py for data analysis.pdf | Assignment 2 report |

## Tools Used
- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Author
London Success Academy — AI/ML Foundations Programme 2025
