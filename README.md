# Report on Time Use Survey: A Statistical Analysis of Finnish Household Habits

### Statistical Data Analysis Course Project Assignment

## 📋 **Project Overview**

This project performs a comprehensive statistical analysis of the "Time Use Survey" data provided by Statistics Finland. The goal was to characterize the daily habits of 780 Finnish individuals and households, specifically focusing on activities like working, sleeping, and reading.
The analysis transitions from raw data cleaning to advanced multivariate modeling to identify behavioral patterns across different demographic groups, including sex, age, and living environments.

This project was completed using Google Colab and demonstrates data analysis and modelling in Python.


## 🔍 **Key Technical Implementations**

- **Data Cleaning & Imputation:** Standardized inconsistent time formats (HH:MM to minutes) and handled missing values using group-wise median imputation.
- **Principal Component Analysis (PCA):** Reduced dimensionality of activity variables, with the first two components explaining 80% of total variance.
- **K-Means Clustering:** Segmented the population into two distinct behavioral clusters: a "Working Group" and a "Leisure/Non-working Group".
- **Hypothesis Testing:** Conducted Kruskal-Wallis and Mann-Whitney U tests to determine significant differences in habits based on living environment and day of the week.
- **Correlation Analysis:** Utilized Spearman’s Correlation to uncover the significant negative relationship between work and sleep duration.


## 📈 **Major Findings**

- **The Sleep Standard:** Finnish households average 8.83 hours of sleep daily.
- **Age-Driven Habits:** Reading frequency increases significantly with age, with the 75+ group reading for approximately 2 hours daily.
- **Environmental Impact:** Residents in rural areas spend significantly more time sleeping compared to those in cities and municipalities.
- **Weekend Flexibility:** While working days average over 7 hours of work, Finns still contribute approximately 4 hours of work on weekends.

## 📂 **File Structure**
- **Analysis Code.ipynb:** Full Jupyter/Colab notebook containing data processing and models.
- **Project Final Report.pdf:** The comprehensive executive report presented to the Board.
- **habits.data:** The primary dataset sourced from Statistics Finland.
- **habits.txt:** Assignment instruction and documentation about the datasets

## Tools
- Python
- pandas
- numpy
- sklearn
- scipy.stats
- matplotlib
- statsmodels
- scikit-learn


## How to run

Open the notebook in Jupyter or Google Colab

## Contact

This project was completed by **Dominic Amoateng Sabeng, Nouman Bashir** and **Saif Ur Rehman** under the supervision of **Juhu Heimonen** in October, 2025. For questions or feedback, kindly contact or open an issue with the author @ wondersabeng@gmail.com or dasabe@utu.fi

## How to Cite This Project

If you use this analysis or the associated code in your own research, please cite it as follows:

*APA Style:* Bashir, N., Sabeng, D. A., & Rehman, S. U. (2025). Report on Time Use Survey: A Statistical Analysis of Finnish Household Habits. University of Turku, Department of Computing.


## License
Code and Analysis 

This project is licensed under the MIT License. This means you are free to use, copy, modify, and distribute the code, provided that the original copyright and permission notice are included.

Data 

The dataset used in this analysis is derived from the "Teaching Use Data of the Time Use Survey" by Statistics Finland. It is used under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence. Any redistribution of the data must credit Statistics Finland accordingly.


