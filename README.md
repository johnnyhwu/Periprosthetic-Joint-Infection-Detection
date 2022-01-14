# Periprosthetic-Joint-Infection-Detection

## Background

```
This is a term project of 2021 Data Mining Course in National Yang Ming Chiao Tung University 
```

Total knee/hip joint replacement (total knee/hip arthroplasty) is performed to restore function and relieve pain in patients with severely damaged knees. 
The surgery involves replacement of both the medial and lateral femorotibial joints and the patellofemoral joint. Although total joint replacement is an effective 
treatment, postoperative complications include blood clots, infection, and loosening or malalignment of the prosthetic component. Periprosthetic joint 
infection (PJI) is a serious complication occurring in 1% to 2% of primary arthroplasties, which is associated with high morbidity and need for complex 
interdisciplinary treatment strategies.

## Objective
This Project aims to encourage the development of algorithms for detecting the periprosthetic joint infection (PJI) from medical records. An accurate early PJI diagnosis can help doctors proceed with further necessary and appropriate treatments.

We will learn how to preprocess dataset, and use different kinds of models (Autoencoder, Decision Tree, Random Forest, Support Vector Machine and Logistic Regression) to classify. The detailed specification of this project, please refer ****spec.pdf****.

## Project Structure
- ./
  - ****main.ipynb**** : all the code is in this file
  - ****report.pdf**** : simple report for this project based on ****spec.pdf**** (report is written in Traditional Chinese)
  - ****spec.pdf**** : specification published by TA for this project
  - ****README.md****
- ./dataset
  - ****train.xlsx**** : training dataset
  - ****test.csv**** : testing dataset without label
  - ****processed**** : the directory contains the serialized model (onnx format), processed training and testing dataset for all kinds of models defined in ****main.ipynb****.

## Data Description
We have posted 52159 of the joint replacement surgical patient records and labels as public training sets and kept 980 records as private test sets.

## Run
The simplest way to run **main.ipynb** is open this repository in google colab. If you want to run on your local environment, make sure the path of dataset is set correctly.

