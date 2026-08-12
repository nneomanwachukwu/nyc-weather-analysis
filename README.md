# 31-Day NYC Weather Analysis

> **Cleaning data is not a preliminary task—it is the analysis that makes every subsequent insight trustworthy.**

This project documents an end-to-end exploratory analysis of a 31-day New York City weather dataset using **Python**, **Pandas**, and **Plotly Express**. Starting with raw weather observations stored in a CSV file, the project systematically evaluates data quality, resolves inconsistencies, explores the statistical behaviour of weather variables, investigates relationships between them, and communicates the results through interactive visualisations.

Rather than simply producing charts, the notebook demonstrates a disciplined analytical workflow that mirrors how real-world datasets are prepared before business decisions are made.



# The Problem

Raw datasets are rarely ready for analysis. Missing values, inconsistent entries, incorrect data types, and duplicate records can all lead to misleading conclusions if left untreated.

The purpose of this project is to demonstrate a practical workflow for transforming raw weather observations into a reliable dataset suitable for exploration, statistical analysis, and visualisation.



# Dataset

**Source:** New York City Weather Dataset

**Period Covered:** 31 Days

**Format:** CSV

The dataset contains daily weather observations including:

- Temperature
- Dew Point
- Relative Humidity
- Sea Level Pressure
- Wind Speed
- Visibility
- Precipitation
- Weather Events



# Tools Used

| Tool | Role |
|------|------|
| Python | Programming Language |
| Pandas | Data Cleaning & Analysis |
| Plotly Express | Interactive Visualisations |
| Jupyter Notebook | Development Environment |



# Project Workflow

## Data Import

The project begins by importing the weather dataset from a CSV file using a reusable Python function with basic exception handling to improve reliability and code reusability.



## Data Understanding

Before making any changes, the dataset is explored to understand its structure and overall quality.

The notebook examines:

- Dataset dimensions
- Sample records
- Column names
- Data types
- Missing values
- Duplicate records
- Descriptive statistics

This initial exploration provides a clear understanding of the condition of the dataset before preprocessing begins.



## Data Cleaning

To prepare the dataset for meaningful analysis, several cleaning operations are performed.

These include:

- Identifying missing values
- Detecting duplicate records
- Replacing trace precipitation values (`T`)
- Filling missing observations where appropriate
- Converting variables into appropriate data types
- Reorganising columns into a cleaner structure

These steps improve consistency and analytical reliability.



## Exploratory Data Analysis

After cleaning, the notebook investigates the statistical characteristics of the major weather variables.

The analysis focuses on:

- Temperature
- Dew Point
- Relative Humidity
- Sea Level Pressure
- Wind Speed

Summary statistics are generated to understand the distribution, spread, and central tendency of each variable.



## Correlation Analysis

The project examines relationships between numerical weather variables using correlation analysis to identify patterns and measure the strength of associations within the dataset.



## Interactive Visualisation

The analysis concludes with interactive visualisations built with Plotly Express, allowing weather variables to be explored visually and making trends easier to interpret.



# What This Project Demonstrates

This project demonstrates the ability to:

- Import external datasets into Python.
- Assess data quality before analysis.
- Clean and prepare real-world data.
- Explore datasets using descriptive statistics.
- Analyse weather variables individually.
- Investigate relationships between variables.
- Build interactive visualisations.
- Apply a structured exploratory data analysis workflow.



# Repository Structure

```text
nyc-weather-analysis/
│
├── nyc_weather.csv
├── nyc-weather-analysis.ipynb
├── README.md
└── images/
    ├── temperature-analysis.png
    └── correlation-heatmap.png
```



# Project Preview

## Temperature Analysis

![Temperature Analysis](images/temperature-analysis.png)



## Correlation Heatmap

![Correlation Heatmap](images/correlation-heatmap.png)



# Key Takeaway

This project reinforces an important principle in data analytics:

> Reliable insights begin with reliable data.

By systematically inspecting, cleaning, validating, and exploring the dataset before interpretation, the analysis establishes a dependable foundation for understanding weather patterns and supporting further analytical work.




**Author**

**Nneoma Nwachukwu**
