# piwi--interacting-RNAs-disease-association-prediction-using-Auto-LGBM
I constructed a model using a unique combination of Autoencoder Neural Networks and Light Gradient Boosting Machine (LightGBM) for predicting the disease associated piwi-interacting RNAs.
## Overview
In this project, we explore the potential of autoencoder neural networks to unveil intricate patterns and representations within the dataset. These learned features are then fed into LightGBM, a powerful gradient boosting framework, to build a robust predictive model for disease associations
##Datasets
1. DIS_s.txt provides the disease similarity matrix of 22 diseases constructed using disease functional similarity and gaussian interaction profile kernal similarity.
2. RNA_S.txt is the RNA similarity network constructed from RNA functional similarity and gaussinal interaction profile kernal similarity network.
3. D_R_A.txt is the complete association of diseases and RNAs.
## Methodology highlights
###Autoencoder
Discover subtle relationships and features within the data using autoencoder neural networks by reducing the dimensionality from 523 feature vectors to 128.
###LightGradientBoostingMachine
Leverage LightGBM to enhance the model's predictive capabilities based on the insights gained from the autoencoder.
###Dataset
The models are trained and evaluated on an experimentally verified dataset, ensuring the reliability and real-world relevance of predictions.
###5-fold validation
The performance of model is evaluated by 5-fold cross validation as well as the performance metrics abd ROC curve.
