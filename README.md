# Vinho Verde Dataset Analysis

Project developed for the Mathematics for Machine Learning master course at Polythecnic of Turin.

The goal of the project was to study a dataset and apply some classification or regression algorithms. Detailed [report](https://github.com/MauriVass/VinhoVerdeDatasetAnalysis/blob/master/VinhoVerdeAnalysisReport.pdf).

## Introduction
This is the analysis of [Vinho Verde wine dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality) that contains two different types of wine: red and white. The task is to build a model in order to predict wine quality given its psychochemical characteristics.

## Data Exploration
Phase of the analysis is exploring data in order to obtain the highest possible number of information before applying models.  
> Input features: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH,  alcohol,  sulphates.

> Output variables: quality (score between 0 and 10), label (derived from the quality feature: low and high quality labels).

Other steps of the data exploration are: check for null values, duplicates values, quality distribution, univariate analysis, bivariate analysis.

## Preprocessing
In the preprocessing part, data is processed in order to make it suitable for the different machine learning algorithms.

The steps are: standardization, dimensionality reduction (PCA) and split dataset.

## Model Application

The problem is solved both as a regression and classification task so the machine learning algorithms used are suitable for both regression and classification. These algorithms are: SVM, KNN, Random Forest.

## Extra
Since the classes were unbalanced, some balancing algorithms were used: SMOTE, ADASYN. These methods allowed to get similar accuracy score but most importantly the models were able to predict classes that previously they could not due to the very low number of elements for those classes.

