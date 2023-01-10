# Udacity Arvato Capstone Project

## Description
This repository contains an analysis of the Arvato data provided during the "Data Science" Nanodegree program. Due to the terms and conditions of the data, the data itself cannot be uploaded to GitHub. 

The Notebook starts with __Exploration__ and __Cleaning__ of the data and then tries to find customer segments via __Clustering__.
In the final step we predict whetever we should target a customer or not by using __Classification__.


## How-To
The IPython Notebook is the only file needed. Just ensure you have the `numpy` and `pandas` installed, you can install it via `pip install numpy`. Other dependencies will be installed inside the Notebook.

## Results
| | RSLVQ | RSLVQ + SMOTE|RUSBoost|XGBoost|XGBoost + SMOTE|GradientBoosting|GradientBoosting + SMOTE|Balanced RF|
|----|-------|---|---|---|---|---|---|---|
|Accuracy|97.62|98.06|68.50|98.65|98.65|98.50|98.65|98.58|
|Kappa|0.43|-0.82|1.3|0.0|0.0|-0.26|0.0|1.18|

### Final Result for Balanced RF after Grid Search (w.r.t. Kappa score)
Accuracy: 58.71,
Kappa: 2.24

## Acknowledgements
We want to thank Bertelsmann Arvato Analytics for providing the dataset and we are also thankful, that Udacity brought up this interesting project. Huge thanks goes to the open source community, for providing dataset libraries and knowledge around them.