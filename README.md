# Do (wo)men talk too much in films?
## Introduction
Machine Learning nowadays is an attractive approach when it comes to prediction or classification based tasks. In a typical ML workflow, datasets are analyzed to generate insights, and then models are trained to predict/classify these data given a target(s). 


This project is based on a study that looked at film dialogues specifically for Hollywood movies to examine if men dominated movie roles and how certain components of the movies influenced that.


We will predict the lead actor in a Hollywood film, which can be male or female, for this project. The dataset includes various information about the films such as films' year of release, gross, number of actors, and quantity of words. The goal is to examine how well we can predict the lead actor using the provided dataset, and then to investigate how different features (properties in the dataset) are associated and affect our result. As this is a classification problem, a few classification models will be explored and compared. Only one model will be chosen, which in turn will be used to test on new unseen data.
## Table of Contents
* Exploratory Data Analysis
* Feature Engineering
* Models Evaluation
* Hyperparameter Tuning
* Models Training
* Model Testing


## Conclusions and Reflections
In this brief study, we trained, evaluated and tested a plethora of classifiers ranging from linear models (Linear regression, LDA), to non linear: bagging models, boosting models...using the Hollywood Movie Actors dataset to predict the gender of the lead (and indirectly the co-lead) actor. The performance results showed the superiority of the boosting classifiers, especially XGBoost and LightGBM with an F1 score of 88.7\% and 87.3\% respectively on the test data. These results should be taken at face value, since we don't know how this dataset was curated in the first place, nor if it is a good representation of the actual Hollywood movies. We think that features such as the  'genre', 'movie's budget', 'Producer gender', 'Director gender', 'Screenwriter gender' can provide more insights. We know for a fact that the writer, director and the producer control the scenarios and the casting. 

Assuming that the provided dataset is a good representation of the Hollywood movies, then we can conclude that men do speak more than women. 
