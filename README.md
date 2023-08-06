# [Pima Indians Diabetes Analysis](https://github.com/jcawesome/jcds-mit-foundations-of-data-science/blob/main/Project%20Assessment%20-%20Foundations%20of%20Data%20Science/Notebook_Pima%2BDiabetes%2BAnalysis_JCMP.ipynb)

## Introduction
In this notebook, I will try and use different techniques I have learned from the **Foundations of Data Science** course under the MIT - "Data Science and Machine Learning: Making Data-Driven Decisions" Program.

## Business Case
**Context:** 
> To analyse different aspects of Diabetes in the Pima Indians tribe.

Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe. In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima tribe.

**Problem:** Analyzing Different Aspects of Diabetes in the Pima Diabetes Analysis Dataset via **Exploratory Data Analysis**

The notebook is divided into different sections:
* Data Dictionary
* Import Libraries
* Data Loading and Initital Summary Statistics
* Data Visualization
* Summary

## Summary
* As expected, there are medium correlations which are indicated by the 'red' color in the heatmap such as age vs pregnancies and bmi vs skin thickness. 
* An important correltation to take note is the correlation to Diabetes Pedigree Function (which scores the likelihood of diabetes based in family history): Glucose, Skin Thickness, Insulin and BMI have almost the same correlation with the aforementioned variable.
* The analysis shows that those who are less than 30 got the same frequency of having or not having diabetes. However, more women from the Pima Indian tribe shows signs of diabetes early before the age of 50.

## Future Improvements
This project assessment involves breaking down the analysis thru a series of questions. To further improve on this notebook, I should do the following:
* Include additional analysis that is not asked as part of the assessment
* Explore other relationships between the variables
* Use different data visualisations
* Compare datasets between Pima Indians tribe with other tribes or other races to see if there is a significant difference in getting affected by Diabetes

