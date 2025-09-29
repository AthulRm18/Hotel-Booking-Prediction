Hotel Booking Cancellation Prediction

This repository contains a machine learning project to predict hotel booking cancellations using a Random Forest Classifier. The model is built within a Scikit-learn Pipeline, ensuring a reproducible and robust workflow.

🚀 Overview
The goal is to predict whether a hotel booking will be canceled based on historical booking data. This model can help hotel managers optimize their booking policies and revenue.
🛠️ Tech Stack
Python

Scikit-learn: For the ML Pipeline, Random Forest model, and feature selection.

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For data visualization.

✨ Key Features & Methodology
Data Cleaning: Handled missing values and outliers to prepare a clean dataset.

Feature Selection: Employed Mutual Information to identify and select the most predictive features, improving model efficiency and performance.

ML Pipeline: Used a Scikit-learn Pipeline to chain preprocessing and modeling steps, preventing data leakage and simplifying the workflow.

Modeling: Trained a Random Forest Classifier, a powerful ensemble method, to achieve high accuracy.

--Results--
The final model achieved an accuracy of 83% on the unseen test set. The classification report confirms its effectiveness in distinguishing between canceled and non-canceled bookings.
