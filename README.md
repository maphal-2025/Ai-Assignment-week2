# Ai-Assignment-week2

Sleep Health and Lifestyle Dataset
This project aims to analyze and preprocess a dataset related to sleep health and associated lifestyle factors. It prepares the data for further exploration and predictive modeling, such as identifying sleep disorders based on health indicators.

Dataset Overview
The dataset includes 374 entries and contains the following attributes:

Personal demographics: Person ID, Gender, Age, Occupation

Lifestyle factors: Sleep Duration, Physical Activity Level, Stress Level, Daily Steps

Health indicators: Quality of Sleep, BMI Category, Blood Pressure, Heart Rate

Target variable: Sleep Disorder (None, Sleep Apnea, Insomnia)

Preprocessing Steps
Data Cleaning

Removed duplicate entries to maintain sample integrity.

Validated absence of missing values using df.isnull().sum().

Feature Engineering

Parsed Blood Pressure into two numeric features: Systolic and Diastolic.

Categorical features converted into dummy/one-hot encodings.

Normalization

Applied Min-Max scaling to numerical features:

Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, Heart Rate, Daily Steps.

Dataset Splitting

Features (X) and target (y) were separated.

An 80/20 train-test split was applied using train_test_split.

Usage
All preprocessing is implemented in Python using libraries such as pandas, numpy, and scikit-learn.

bash
pip install pandas numpy scikit-learn
Goals
This dataset can be used for:

Exploring correlations between lifestyle habits and sleep quality

Predictive modeling for detecting sleep disorders

Supporting innovations in wellness tech (e.g. apps like RestWell)
