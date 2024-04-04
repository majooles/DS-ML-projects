# Breast Cancer Prediction Project Overview

In this project, my aim is to predict breast cancer diagnosis (malignant or benign) using machine learning techniques. I'll be working with a dataset containing various features derived from cell nuclei.

## Tools and Libraries Used

I'm using pyspark for distributed computing and machine learning tasks.

## Data Preprocessing

I start by loading the dataset and performing basic data exploration. I handle missing values and drop unnecessary columns like 'id' and '_c32'. Then, I convert the 'diagnosis' column into numeric labels using StringIndexer.

## Feature Engineering

I use VectorAssembler to combine all the feature columns into a single vector, which is required for modeling.

## Model Training

I train a logistic regression model on the transformed dataset. After training, I evaluate the model's performance using metrics like AUC-ROC, accuracy, precision, and recall.

## Manual Metric Calculation

I also delve into manual calculations of metrics like false positives, false negatives, true positives, true negatives, recall, accuracy, and precision to gain a deeper understanding of each metric's significance.

## Results

The trained model achieves an accuracy of 0.92, indicating its ability to correctly classify breast cancer based on the given features.

This project demonstrates the effectiveness of machine learning in diagnosing breast cancer, providing valuable insights for medical practitioners.
