# Introduction
In this notebook, we are going to go through the entire data science workflow to build models, analyze models and select the best model to solve our problem.

## 1.1 Problem Statement

We are challenged to determine people's perception on climate change, whether they believe that climate change is real and if it is a threat. We shall create a machine learning model that uses natural language processing to determine a person's view on climate change based on their tweet data. We aim to come up with a viable model that is able to accurately classify people into groups of those who believe and those who do not. With this we will be able to offer insights to marketing departments on how well or badly their product will be recieved on the market based on its effects on the climate. This will help marketing teams to come up with strategies on how to run their campaigns in the future.

## 1.2 The dataset

we are provided with a dataset containing tweets collected from 27/04/2015 to 21/02/2018. The dataset contains three features;

sentiment - the class in which a tweet belongs ranging
from -1 to 2

message - The body of the tweet provided

tweetid - a unique identifier for each tweet

The dataset is split into training data and test data with training data containing 80% of the data
