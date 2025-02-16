**Project Overview**
This project analyzes Instagram engagement metrics to identify trends, detect anomalies, and derive actionable insights for improving social media performance.

**Dataset**
The dataset consists of 119 Instagram posts with 13 columns containing various engagement metrics, including:
Impressions (Total reach of a post)
From Explore (Views from the Explore page)
Follows (New followers gained from a post)
Likes, Comments, Shares, Saves (User interactions)
Captions and Hashtags (Text-based engagement factors)

**Key Features**
Outlier Detection & Correction: Applied IQR method to cap extreme values and maintain data integrity.
Data Cleaning & Preprocessing: Checked for missing values and standardized numerical variables.
Exploratory Data Analysis (EDA): Visualized distributions, trends, and correlations.
Feature Engineering: Created an Engagement Rate metric to quantify post performance.
Predictive Analysis: Implemented regression models to predict reach and interactions.

**Visualizations**
Boxplots to compare engagement metrics before and after outlier correction.
Correlation heatmaps to identify relationships between features.
Histograms and KDE plots for data distribution insights.

**Results & Insights**
Higher saves and shares correlate with better post reach.
Hashtags and captions play a significant role in engagement.
Cleaning and preprocessing data significantly improved model accuracy.
