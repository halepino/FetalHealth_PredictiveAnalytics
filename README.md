# Fetal Health Predictive Analytics

## Overview

This project aims to develop a predictive model to assess the health of fetuses based on various parameters collected during cardiotocograms (CTGs).  
The dataset used for this project contains features such as fetal heart rate (FHR), uterine contractions (UC), etc., which are utilized to predict fetal health status.

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

## Notebook Content

- **Data Preparation**: 
  - Data loading
  - Data cleaning
  - Exploratory data analysis (EDA)
  - Feature engineering

- **Model Building**:
  - Selection of machine learning algorithms
  - Model training
  - Model evaluation

- **Results**:
  - Performance metrics of the trained models
  - Visualization of results
  
## Requirements

To run the notebook and reproduce the results, you'll need the following dependencies:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (e.g., pandas, scikit-learn, matplotlib)

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/halepino/FetalHealth_PredictiveAnalytics.git
