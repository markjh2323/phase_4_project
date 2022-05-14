# phase_4_project
NLP: Sentiment Analysis of Tweets

## Overview
Social Media is a key tool used by companies for marketing and market research. It allows companies to get a feel for how the public is perceiving their brand, product, or service. It is also much more economically feasible than other methods of marketing and market research. Twitter is one of the most used social media platforms in the world. It allows users to share a few words in a Tweet, which can include how the person feels about a product.

## Business Problem and Data Understanding
We decided to conduct a Sentiment Analysis to provide businesses with an idea of the overall sentiment they are receiving on Twitter. Our model aims to predict whether tweets are positive or negative. Our data is 9,000 tweets collected and by CrowdFlower about products/brands such as Google, Apple, iPhone, Android, etc. They were labelled by human contributors as Negative, Neutral, and Positive. 

## Modeling and Evaluation
We decided to try multiple models, with our final models being the Support Vector Machine(SVM) model and the Complementary Naive Bayes(CNB) model. We decided to go with these two because the CNB model performed with a 0.80 accuracy and was optimized for false positives, providing a more conservative picture, while the SVM model performed with a 0.88 accuracy, and was optimized for false negatives, providing a more optimitic picture of the sentiment. 

## Conclusion 
Our models were accurate in demonstrating the sentiment that the products were generating on Twitter. In order to improve these models, we will be looking into adding more data for the model to train, as well as implementing the use of Neural Networks in order to increase the accuracy. 