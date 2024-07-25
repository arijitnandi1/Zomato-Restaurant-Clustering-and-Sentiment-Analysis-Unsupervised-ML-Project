# Zomato-Restaurant-Clustering-and-Sentiment-Analysis-Unsupervised-ML-Model



## Table of Contents

- Introduction
- Project Overview
- Preprocessing Data
- Feature Engineering
- ML Model Implementation
- Conclusion

## Introduction

Welcome to the Machine Learning Capstone Project, a comprehensive exploration of data preprocessing, feature engineering, model implementation, and evaluation. This project aims to demonstrate the complete lifecycle of a machine learning project, from data preparation to model deployment.

## Project Overview

- **Data Collection:** I started by collecting data related to customer reviews, restaurants, and other relevant information.

- **Data Preprocessing:** Extensive data preprocessing was carried out to handle missing values, clean the data, and prepare it for analysis.

- **Feature Engineering:** I created new features, removed redundant ones, and applied various text preprocessing techniques to enhance the quality of the data.

- **ML Model Implementation:** I implemented two machine learning models: K-means clustering and Latent Dirichlet Allocation (LDA) to gain insights from the data.

- **Model Evaluation:** The models were evaluated based on various metrics, including Silhouette Score, ROC AUC, and more.

## Preprocessing Data

- Data collection included reviews, restaurant information, and more.
- Extensive data cleaning and handling of missing values.
- Text preprocessing, including expansion of contractions, lowercasing, and removal of punctuation, URLs, digits, stopwords, and whitespace.

## Feature Engineering

- New features were created to minimize feature correlation.
- Sentiment analysis was performed on reviews, classifying them as positive or negative based on average ratings.
- The 'Cost' feature was log-transformed to address positive skewness.

## ML Model Implementation

Two machine learning models were implemented:

- **K-means Clustering:** Data was clustered into 6 groups to gain insights into restaurant features.
- **Latent Dirichlet Allocation (LDA):** Used for topic modeling and analysis of customer reviews.

## Conclusion

- Significant improvements were observed in the clustering results, especially in the selection of an appropriate value for K.
- The LDA model was fine-tuned to improve the Silhouette Score.
- Extensive model evaluation, including ROC AUC, precision, recall, and more, was performed.
- The project provides a comprehensive guide on how to go from data preprocessing to model implementation and evaluation.

Start exploring the project for more details and insights!

Feel free to contribute, report issues, or ask questions. Happy coding!
