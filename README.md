# lego-analysis

Author: M. Tosic
Date: 02.2022

## Description:
This script represents the implementation of the CRISP-DM process for data analysis of the development of lego sets during the past thirty years. Datasets are gathered together and the data is explored and prepared for further analysis. Subsequently, different questions are answered using descriptive statistics and different kinds of visualizations. This repo is to be submitted as part of a project assignment in a data science course.

A Medium article about this project is available here:
https://medium.com/@michaeltosicde/three-decades-of-lego-a-data-science-project-2842c778e088

**Questions of interest**
1. What number of sets and themes was launched every year since 1991?
2. What themes were available over the years and with how many sets?
3. What were the yearly top ten most dominant themes by a number of sets?
4. What were the record-breaking sets by piece count?
5. Do sets have more and more pieces in general?
6. What words do most often come up in set names?
7. Are lego sets becoming more and more expensive?
8. How does the value of lego sets change after they are not actively produced anymore (eol)?
9. What themes do best after eol?

The answers are determining from the mentioned data set by extracting the information, transforming it into the necessary form and displaying the visualization.

*eol = lego-term for end-of-life meaning the date when the set is not being produced

## Motivation
This project work is part of my online course on data science. I chose to find new datasets rather than to work with the suggested ones and since I am very interested in Lego since my childhood, I've decided to analyze lego sets from my birth year 1991 to today. :)

### Mini-Disclaimer
This notebook is part of my capstone project for a data science course. The project is independent and has no connection to the company LEGO. I am very much a beginner in data analysis and have created this notebook as one of my projects in an online course. Please don't take the conclusions I have made too seriously. If you have suggestions for improvement or insight into maybe some errors I've made, please feel free to let me know.


## Installation
An Anaconda distribution and the following packages are required:
* Python 3.9.7
* matplotlib    3.4.3
* matplotlib-inline 0.1.2
* nltk  3.6.5
* notebook  6.4.5
* numpy 1.20.3
* pandas    1.3.4
* plotly    5.5.0
* regex 2021.8.3

## Sources
Data being used in this notebook has been downloaded from the following sources:

Lego datasets:
* https://brickset.com/

Currency exchange rates:
* www.macrotrends.net

Consumer Price Index (CPI):
* https://fred.stlouisfed.org/series/CPIAUCSL

## Project Structure:
The project is made out of the following files:
* lego-analysis.ipynb as the main jupyter notebook
* all datasets are stored in the folder /data as csv files

## CRISP-DM process
A requirement for the project is also to show the implementation of the CRISP-DM process:

1. Business Understanding
2. Data Understanding
3. Prepare Data
4. Data Modeling(Optional)
5. Analysis & Evaluation of Results
