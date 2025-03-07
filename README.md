# Hurricane_project
Analyzing Hurricane Impact through Sentiment and Fatality Prediction

Hurricane Impact Prediction and Sentiment Analysis

This project focuses on predicting the number of fatalities caused by hurricanes and performing sentiment analysis on tweets related to hurricanes. The goal is to understand the relationship between the strength of hurricanes, the scale of destruction, and public sentiment. The project utilizes machine learning models, such as XGBoost and DecisionTreeRegressor, to make predictions and analyze social media data for insights into how people react to natural disasters.

Key Features:
Fatality Prediction: Develop a predictive model to estimate the number of fatalities based on hurricane strength and related features.

Sentiment Analysis: Analyze public sentiment in tweets related to hurricanes, investigating how the strength and damage caused by hurricanes correlate with the emotional tone of the tweets.

Data Preprocessing and Feature Engineering: Clean and transform data from multiple sources to be used in predictive modeling.

Model Evaluation: Use performance metrics like accuracy, precision, recall, F1-score, and RMSE to evaluate the models.

Data Sources:
Hurricane Data (Fatalities & Characteristics):
The database used for hurricane characteristics, including fatalities, was created by another student (Daniel Allen) based on publicly available data from the National Oceanic and Atmospheric Administration (NOAA). This dataset contains hurricane features like wind speed, damage, and the resulting fatalities.

Tweet Data:
Tweets related to hurricanes were collected from the following sources:

CrisisNLP: Hurricanes Tweets Collection (https://crisisnlp.qcri.org/humaid_dataset)
Kaggle: Tweets for Hurricane Harvey (https://www.kaggle.com/datasets/dan195/hurricaneharvey)
GitHub: Tweets for Hurricane Michael and Florence (https://github.com/Nassery99/Twitter-Credibility-Analysis-Hurricane-Florence-And-Michael-Datasets)

Technologies Used:
Python for data manipulation and machine learning model development.
Scikit-learn and XGBoost for predictive modeling.
Pandas for data cleaning and feature engineering.
Matplotlib and Wordcloud for data visualization.
NLTK and TextBlob for sentiment analysis.
