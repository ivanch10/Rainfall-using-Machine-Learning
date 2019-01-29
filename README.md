# Rainfall using Machine Learning 
In this project we will work with a dataset of satellite-based meteorological measurements
used to predict rainfall at a particular location. The dataset has been pre-processed to extract
features corresponding to a model actively used for predicting rainfall across the globe. Each data
point corresponds to a particular lat-long location where the model thinks there might be rain.
The extracted features include information such as IR (cloud) temperature at that location, and
information about the corresponding cloud (area, average temperature, etc.). The target value is
the amount of rainfall at the particular location..

# Introduction
In this project, we will work with meteorological measurements data that predicts rainfall at different locations. Three learners, Random Forest, KNN, and Linear Regression, are implemented, and optimized by choosing the best parameters. The individual results from the learners are then analyzed and compared amongst each other based on their Mean Squared Error (MSE).

The objective is to test and analyze the performance of various prediction techniques: Random Forest, KNN, and Linear Regression.

# B. Steps in tuning Random Forest Parameters
1. Determine best Maximum depth in Decision Tree where the Decision Tree function is provided in mltools library.
2. Determine best Minimal Number of Leafs in Decision Tree.
3. Determine best Number of Features in Random Forest with optimal Maximum Depth and Minimal Number of Leafs where the Random Forest function is provided in mltools library.
4. Determine best Number of learners in Random Forest with optimal Number of Features, Maximum Depth, and Minimal Number of Leafs.

# Results:
Optimal Values of Parameters: Maximum number of Depth = 4, minimal number of Leaf = 2**8, Number of Features = 8, Number of learners = 20
Scores:
MSE = 3.66 in validation data
Kaggle score = 3.48732
The MSE in validation data is closed to Kaggle score.
