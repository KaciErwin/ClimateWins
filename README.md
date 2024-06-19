# ClimateWins Analysis

## Introduction
Climate Wins, a European nonprofit organization dedicated to understanding and mitigating the impacts of climate change, aims to leverage machine learning to predict future weather conditions and potential extreme weather events in mainland Europe. By analyzing historical weather data, we hope to use machine learning algorithms to develop models that can provide insights into temperature trends, extreme weather patterns, and overall climate variability. 

## Project Objectives
The analysis aims to adress several key questions to aid ClimateWins objective:

+ Finding new patterns in weather changes over the last 60 years.
+ Identifying weather patterns outside the regional norm in Europe.
+ Determining whether unusual weather patterns are increasing.
+ Generating possibilities for future weather conditions over the next 25 to 50 years based on current trends.
+ Determining the safest places for people to live in Europe within the next 25 to 50 years.

## Data
The data used by ClimateWins is the European Climate Assessment and Dataset (ECA&D), collected and funded by the Royal Netherlands Meteorological Institute (KNMI). The ECA&D includes a wide range of weather information, such as temperature, precipitation, wind speed, and humidity, from 18 weather stations across Europe. It spans multiple decades, enabling detailed analysis of historical weather patterns and trends. The data from the ECA&D is meticulously collected and validated by the KNMI to ensure high accuracy and reliability. The weather stations are strategically located across Europe, providing a representative sample of the continent's diverse climate conditions. 

## Methodology
This project employs a range of machine learning techniques to assess climate variability and predict future weather conditions. 

Machine Learning Techniques
+ Supervised Learning
  + Linear Regression: Identify trends in temperature changes over time.
  + K-Nearest Neighbors: Classify weather patterns.
  + Decision Tree: Classify weather patterns and predict extreme weather events. 
  + Random Forest: Identify key locations and climate variables that contribute most to data variance
+ Unsupervised Learning
  + Principal Component Analysis: Identify the most influential variables to the data patterns.
  + Hierarchical Clustering: Group similar weather patterns and identify anomalies.
  + Convolutional Neural Network: Analyze spatial and temporal patterns in weather data.

Tools and Technologies
+ Python: Primary programming language used for data analysis and machine learning.
+ Scikit-learn: Machine learning library for implementing standard algorithms.
+ TensorFlow: Performing neural architecture searches.

## Deliverables
The repository contains the following deliverables:

+ [Python Code](<ClimateWins Scripts>): Scripts used for data analysis.
+ [Interim Presentation](<ClimateWins Reports/ClimateWins Interim Report.pdf>): An interim presentation providing analysis methods, visualizations, and model recommendations.
+ [Final Presentation](<ClimateWins Reports/ClimateWins Report.pdf>) : A final presentation providing model analysis and future recommendations.
