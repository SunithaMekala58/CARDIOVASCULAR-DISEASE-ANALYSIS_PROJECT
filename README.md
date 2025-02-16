# CARDIOVASCULAR DISEASE ANALYSIS_PROJECT
# Overview:
Cardiovascular disease (CVD) is a class of diseases that involve the heart or blood vessels. Cardiovascular diseases are the leading cause of death globally. This is true in all areas of the world except Africa. Together CVD resulted in 17.9 million deaths (32.1%) in 2015. Deaths, at a given age, from CVD are more common and have been increasing in much of the developing world, while rates have declined in most of the developed world since the 1970s.

I have conducted Exploratory Data Analysis (EDA) of the Cardiovascular disease dataset. As, the primary objective of EDA is to analyze the data for distribution, outliers and anomalies in the dataset. It enable us to direct specific testing of the hypothesis.

This Analysis intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using EDA.

# Table of Contents:

The table of contents for this project are as follows: -
1) Import libraries
2) Import dataset
3) Exploratory data analysis - Check shape of the dataset - Preview the dataset - Summary of dataset - Dataset description - Check data types of columns - Important points about dataset - Statistical properties of dataset - View column names
4) Univariate analysis - Analysis of target feature variable - Findings of univariate analysis
5) Bivariate analysis - Estimate correlation coefficients - Analysis of target and cp variable - Analysis of target and thalach variable - Findings of bivariate analysis
6) Multivariate analysis - Heat Map - Pair Plot
7) Dealing with missing values - Pandas isnull() and notnull() functions 
8) Outlier detection
    

# Data Description:
- The dataset contains several columns which are as follows -

  - age : age in years
  - sex : (1 = male; 0 = female)
  - cp : chest pain type (4 values)
       - Value 0: typical angina
       - Value 1: atypical angina
       - Value 2: non-anginal pain
       - Value 3: asymptomatic
  - trestbps : resting blood pressure (in mm Hg on admission to the hospital)
  - chol : serum cholestoral in mg/dl
  - fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
  - restecg : resting electrocardiographic results
        - Value 0:  Normal,
        - Value 1:  ST-T wave abnormality,
        - Value 2:  Probable or definite left ventricular hypertrophy
  - thalach : maximum heart rate achieved
  - exang : exercise induced angina (1 = yes; 0 = no)
  - oldpeak : ST depression induced by exercise relative to rest
  - slope : the slope of the peak exercise ST segment
         - Value 1: Upsloping
         - Value 2: Flat
         - Value 3: Downsloping
  - ca : number of major vessels (0-3) colored by flourosopy. A higher count may indicate a greater degree of vessel involvement or narrowing,
         which can be associated with more advanced stages of coronary artery disease. 
  - thal : Thalassemia.
         - Types of Thalassemia
          - Value 3: normal
          - Value 6: fixed defect
          - Value 7: reversable defect
  - target : 1 or 0
           - Value 0: stands for absence of heart disease  
           - Value 1: stands for presence of heart disease
    
# Libraries Used:
 1) Pandas (for data manipulation)
 2) Numpy (for working with arrays)
 3) Matplotlib (for data visualization)
 4) Seaborn (for data visualization)
 5) Scipy(for Statistic Understanding)

# Data Analysis:
# Data Correlation:
![image](https://github.com/user-attachments/assets/eff987cd-6010-4814-b8b3-15b2d4a205fc)

# Correlation Analysis:

- 'target' and 'cp' variable are mildly positively correlated (correlation coefficient = 0.43).
- 'target' and 'thalach' variable are also mildly positively correlated (correlation coefficient = 0.42).
- 'target' and 'slope' variable are weakly positively correlated (correlation coefficient = 0.35).
- 'target' and 'exang' variable are mildly negatively correlated (correlation coefficient = -0.44).
- 'target' and 'oldpeak' variable are also mildly negatively correlated (correlation coefficient = -0.43).
- 'target' and 'ca' variable are weakly negatively correlated (correlation coefficient = -0.39).
-'target' and 'thal' variable are also weakly negatively correlated (correlation coefficient = -0.34).







    
