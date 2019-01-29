# Rainfall using Machine Learning 
## A. Introduction
In this project, we will work with meteorological measurements data that predicts rainfall at different locations. Three learners, Random Forest, KNN, and Linear Regression, are implemented, and optimized by choosing the best parameters. The individual results from the learners are then analyzed and compared amongst each other based on their Mean Squared Error (MSE).

The objective is to test and analyze the performance of various prediction techniques: Random Forest, KNN, and Linear Regression.

## B. Steps in tuning Random Forest Parameters
1. Determine best Maximum depth in Decision Tree where the Decision Tree function is provided in mltools library.
2. Determine best Minimal Number of Leafs in Decision Tree.
3. Determine best Number of Features in Random Forest with optimal Maximum Depth and Minimal Number of Leafs where the Random Forest function is provided in mltools library.
4. Determine best Number of learners in Random Forest with optimal Number of Features, Maximum Depth, and Minimal Number of Leafs.

## C. Results:
Optimal Values of Parameters:
Maximum number of Depth = 4, minimal number of Leaf = 2**8, Number of Features = 8, Number of learners = 20

## D. Scores:
MSE = 3.66 in validation data, 
Kaggle score = 3.48732
