📌 Customer Segmentation using K-Means Clustering

A Machine Learning project that segments mall customers into distinct groups based on demographic and spending behavior. Built using Google Colab, Python, and Scikit-learn.

🚀 Project Overview

This project applies K-Means Clustering, an unsupervised machine learning algorithm, to identify customer groups for business insights.

The dataset includes customer demographic information such as:

Gender

Age

Annual Income

Spending Score

Clustering helps businesses design:

Targeted marketing

Personalized recommendations

Customer retention strategies

Product placement and business decisions

🎯 Problem Statement

Businesses want to categorize customers based on their buying habits and demographic information.
The goal is to create meaningful customer segments that help improve marketing strategy and decision-making.

🧠 Objective

Perform data preprocessing and cleaning

Apply K-Means Clustering

Determine the optimal number of clusters using the Elbow Method

Visualize clusters

Interpret customer groups

Provide business insights

📂 Dataset

Mall Customers Dataset

Source: Kaggle

Rows: 200

Columns: 5

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

Note: Some dataset versions use “Genre” instead of “Gender”.

🔧 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Google Colab

🛠 Steps Performed
✔️ 1. Data Loading

Loaded CSV file in Google Colab.

✔️ 2. Data Preprocessing

Renamed “Genre” → “Gender” (if applicable)

Encoded gender (Male = 1, Female = 0)

Checked for missing values

Selected features for clustering

Applied StandardScaler

✔️ 3. Exploratory Data Analysis

Distribution of age, income, and spending score

Gender-wise distribution

Pairplots and correlations

✔️ 4. Elbow Method

Used SSE (Sum of Squared Errors) to determine optimal K.

✔️ 5. K-Means Clustering

Applied algorithm with chosen K

Predicted cluster labels

Added cluster column to the dataset

✔️ 6. Visualization

Scatter plots of clusters

Centroid visualization

Income vs Spending Score plot

✔️ 7. Insights

Identified 4–5 customer groups such as:

High Income, High Spending

High Income, Low Spending

Low Income, High Spending

Low Income, Low Spending

Young shoppers / Elder shoppers

📊 Results & Insights

The model successfully grouped customers into distinct clusters.

Each cluster represents a specific behavior pattern.

These insights can help businesses:

Design better marketing strategies

Improve customer engagement

Provide personalized offers
