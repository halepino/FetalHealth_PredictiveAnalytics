# Fetal Health Predictive Analytics

### Authors: https://github.com/halepino & https://github.com/karliedawn

## Overview

This project aims to develop a predictive model to classify the health outcomes of fetuses based on cardiotocogram(CTG) features. EDA was conducted then Naive Bayes and multi-layer perceptron (MLP) models were trained and evaluated. This repo contains code files for that EDA, Modeling, and Reporting. The complete report is included as a PDF file, but code file also include written rationale. 

## Repo Contents
* FetalHH_EDA.ipynb - Exploratory analysis code file of the dataset with detailed markdown interpretations.  
* FetalHH_Modeling.ipynb - Modeling code file with detailed markdown explainations and evalutation.  
* Predicting Fetal Health Outcomes with Machine Learning.pdf - Final Report  

## Dataset

The dataset used in this project is publicly available and can be found [here](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification). 
It consists of 2126 samples and 22 features. Each sample represents a CTG examination, and the features include:

LB - FHR baseline (beats per minute)  
AC - # of accelerations per second  
FM - # of fetal movements per second  
UC - # of uterine contractions per second  
DL - # of light decelerations per second  
DS - # of severe decelerations per second  
DP - # of prolongued decelerations per second  
ASTV - percentage of time with abnormal short term variability  
MSTV - mean value of short term variability  
ALTV - percentage of time with abnormal long term variability  
MLTV - mean value of long term variability  
Width - width of FHR histogram  
Min - minimum of FHR histogram  
Max - Maximum of FHR histogram   
Nmax - # of histogram peaks  
Nzeros - # of histogram zeros  
Mode - histogram mode  
Mean - histogram mean  
Median - histogram median  
Variance - histogram variance  
Tendency - histogram tendency  
CLASS - FHR pattern class code (1 to 10)   
NSP - fetal state class code (N=normal; S=suspect; P=pathologic)
