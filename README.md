# Spotify Track Popularity Analysis

## Abstract
This project aims to utilize statistical and machine learning techniques to understand the factors influencing the popularity of tracks on Spotify. The analysis revolves around a dataset comprised of track and artist details, diving into various musical features like danceability, loudness, and tempo, among others. Utilizing R, we examine correlations, build logistic regression models, and employ decision trees to deduce significant factors. Further, we also explore the trends of key musical features over the years using time series analysis.

## Objectives
To clean and preprocess the dataset for effective analysis.

To identify and understand the correlations between different musical features and track popularity.

To build predictive models to forecast the popularity of tracks based on their features.

To investigate the temporal trends of key musical features using time series analysis.

## Methodologies
Data Cleaning and Preprocessing: The initial steps involve importing necessary libraries, loading datasets, merging, renaming, and cleaning operations to ensure data integrity for analysis.

Normalization: Features were normalized to ensure comparability and effectiveness of the subsequent analysis.

Correlation Analysis: We performed a correlation analysis to identify significant relationships between different musical features.

Logistic Regression Modeling: Two logistic regression models were built, one with normalized features and another without, to predict track popularity.

Decision Tree Analysis: Decision trees were created to visualize and understand the significant features influencing track popularity.

Stratified and Random Sampling: We used stratified and random sampling methods to split the dataset and compare the performance of decision trees on these splits.

Time Series Analysis and Forecasting: Conducted time series analysis on key musical features to analyze trends over time. Utilized ARIMA model for forecasting, although it was truncated in the provided code.

## Results
The logistic regression models and decision tree analysis yielded an accuracy rate of around 86% in predicting track popularity. Key variables impacting popularity were identified as loudness, danceability, and explicitness. The time series analysis provided insights into the temporal trends of danceability, loudness, and tempo. The decomposition revealed that tempo was stationary while danceability and loudness were semi-stationary over time.

## Discussion
The analysis shows a strong predictive capacity of the chosen models and significant variables that contribute to track popularity on Spotify. However, there are potential improvements and further analyses that could be explored. For instance, the ARIMA model in the time series analysis could be optimized, and other machine learning models could be tested. Moreover, other external factors like artist popularity, album reviews, or real-world events might also play a substantial role in track popularity, and incorporating such data could provide a more holistic analysis.

## Conclusion
Understanding the factors contributing to track popularity can provide valuable insights for artists, producers, and stakeholders in the music industry. While the analysis gives a solid base in identifying key musical features, the exploratory and predictive modeling process could be enriched further with external data and more sophisticated models. Nonetheless, the project underscores the potential of data-driven strategies in understanding and predicting musical success on platforms like Spotify.

## Dependencies
rpart

rpart.plot

caret

ggplot2

tidyverse

tseries

rugarch

dplyr

corrplot

## Datasets
tracks.csv: https://www.dropbox.com/scl/fi/eod3d1b4g9xjjux10ji0u/tracks.csv?rlkey=7jq2rqwyalcxxn5v0sm3pis19&dl=0)https://www.dropbox.com/scl/fi/eod3d1b4g9xjjux10ji0u/tracks.csv?rlkey=7jq2rqwyalcxxn5v0sm3pis19&dl=0
artists.csv: https://www.dropbox.com/scl/fi/e19w0mt817cz22s4jpb8u/artists.csv?rlkey=ky52b6cd49rl1isni0rkht1wu&dl=0)https://www.dropbox.com/scl/fi/e19w0mt817cz22s4jpb8u/artists.csv?rlkey=ky52b6cd49rl1isni0rkht1wu&dl=0
