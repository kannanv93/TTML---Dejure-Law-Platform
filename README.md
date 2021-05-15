# TTML-Dejure-Law-Platform

This repository contains the codes for the Tools for Techniques in Machine Learning course project - Dejure, World Bank.

## Law Platform for Automated Impact Analysis of Judicial Decision

1. Criminal Case Detection.ipynb - Contains the codes for identification of Criminal Cases using Regular Expression
2. Data Cleaning & Meta Data Creation.ipynb - Contains codes for cleaning the data and creating a meta data of all case documents
3. Text Embedding and Treatment Prediction.ipynb - Contains codes for TF-IDF and Doc2Vec along with the model performance on prediction of Treatment variable on 600 manually lablelled cases
4. Modelling Data prepation.ipynb - This code base is a reference for collating multiple datasource, joining Text data with Crime's data from NCBR, Identifying Govt-Petitioner/Respondent etc.
5. Regression Modelling.ipynb - Initially, we tried developing a two stage regression seperately using XGBoost regressor in stage 1 and OLS in stage 2. This was just an experimental work to compare it with standard IV implementation
6. IV TSLS.ipynb - Code base for Instrumental Variable approach with two stage least square regression implementation. 
