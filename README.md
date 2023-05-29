# Statistical-Inference-on-Critical-Habitats-Dataset

This repository contains the code and analysis for my statistics project, which focuses on the "Critical Habitats" dataset obtained from Kaggle. In this project, I performed exploratory data analysis, applied statistical inference methods, and analyzed the correlation between samples. The goal was to gain insights into the critical habitats and assess the statistical significance of the results.

## Table of Contents
Introduction\
Data\
Project Steps\
Results\
Usage\
Dependencies\
Contributing\
License

## Introduction
The purpose of this project was to analyze the "Critical Habitats" dataset to understand the characteristics and relationships between different critical habitats. By applying statistical inference methods, I aimed to draw meaningful conclusions and determine the statistical significance of the results.

## Data
The dataset used in this project is called "Critical Habitats," which was obtained from Kaggle. It consists of [describe the key features and attributes of the dataset].

## Dataset source: Kaggle - Critical Habitats

## Project Steps
The project was divided into the following steps:

### Gather Data:
The "Critical Habitats" dataset was loaded using the pandas library.
### Exploratory Data Analysis (EDA): 
Descriptive statistics were used to explore the dataset, identify patterns, outliers, and missing values.
### Statistical Inference Method: 
Two numerical columns, "ACREAGE" and "GPS_PDOP," were selected for analysis. The data was checked for data type and missing values before proceeding.
### Point Estimation: 
Point estimation was performed to calculate the sample mean of the selected column and visualize the distribution using a histogram.
### Confidence Interval: 
A confidence interval was calculated to estimate the range of values within which the population mean may lie. The confidence interval was visualized using a histogram.
### Hypothesis Testing:
Hypothesis testing was conducted to determine whether the sample mean was significantly different from the population mean using a t-test. The results were interpreted by examining the t-statistic and p-value.
### Correlation Analysis: 
The correlation between the two selected samples was calculated using Pearson's correlation coefficient. The correlation was visualized using a scatter plot.
### Data Visualization: 
Histograms were created to visualize the distributions of the two samples.

## Usage
To reproduce the analysis or explore the project further, follow these steps:

Clone this repository to your local machine using the following command:

git clone https://github.com/AhmadMaazz/Statistical-Inference-on-Critical-Habitats-Dataset.git

Navigate to the project directory:

cd stats-project

Install the required dependencies:

pip install scipy numpy pandas matplotlib seaborn

Execute the analysis script:

python analysis.py

The script will load the "Critical Habitats" dataset, perform exploratory data analysis, and generate visualizations. Review the generated outputs and results for further analysis.

## Dependencies
The following dependencies are required to run the project:

scipy\
numpy\
pandas\
matplotlib\
seaborn

### Install the dependencies using the following command:

pip install scipy numpy pandas matplotlib seaborn

## Contributing
Contributions to this project are always welcome. If you have any suggestions or improvements, please follow these steps:

Fork the repository.\
Create a new branch.\
Make your changes and commit them.\
Push the changes to your forked repository.\
Submit a pull request detailing the changes you made.
