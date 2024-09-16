# Semi-Conductor Performance Prediction

## Overview
This project aims to predict the performance of a semi-conductor manufacturing process using machine learning classification models. I employed various feature selection techniques to identify key factors influencing product yield, allowing for process optimization. The dataset includes 1567 examples with 591 features, and the target label indicates a pass or fail for each production unit.

Due to the class imbalance (most units pass while only a small number fail), I implement techniques such as Random Oversampling and SMOTE (Synthetic Minority Oversampling Technique) to improve the model's ability to detect failures.

## Project Structure

##### Data Preprocessing
##### Handling Missing Values
##### Feature Selection
##### Target Encoding: The target variable (`Pass/Fail`) is encoded as `"PASS"` for pass and `"FAIL"` for fail, which makes the classification task more interpretable.
##### Model Training and Evaluation
