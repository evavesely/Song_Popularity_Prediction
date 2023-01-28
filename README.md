![slide](/figures/cover.png)
## Predicting Song Popularity Based on Acoustic Features

### Overview

Music prediction has been a popular subject in machine learning for a long time, with early work in the field dating back to the early 2000s. Prediction models are extremely useful for the music industry, as both artists and labels need to understand the factors that determine a song’s popularity in order to make decisions. While it has been proven possible to predict a song’s popularity based on factors like its initial debut success and an artist’s social media presence, it is more useful to predict a song’s success independent of any existing popularity, before it is even released.

This was a project developed throughout the entire semester of my SML312 (Research Projects in Data Science) class. My research question was whether it was 
possible to predict the popularity of a song using its acoustic features alone. For this project, I followed the data science life cycle by:

- finding my own datasets 
- performing the necessary data cleaning and exploration
- building baseline models
- optimizing my models with techniques like regularization and hyperparameter tuning

I used several Python libraries including NumPy, pandas, and sklearn's classification models.

### Results 

In the end, I was able to:

- predict song popularity using a random forest classification model with 78% accuracy after hyperparamter tuning
- determine the most important features for predicting song popularity, which are instrumentalness, loudness, danceability, speechiness

Check out my final writeup or my website for more details! Here are some cool figures: 

![data](/figures/data.png)

A preview of one of the datasets I used and its acoustic features

![class](/figures/class.png)

The confusion matrix and accuracy scores for my best model (optimized random forest)

![features](/figures/class.png)

The most important features for that model


