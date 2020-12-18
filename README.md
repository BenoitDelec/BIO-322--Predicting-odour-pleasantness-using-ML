# Bio322-mini-project

# R Version
The R version that is used to run the project is the "R version 3.6.1 (2019-07-05)". 

# Libraries
The libraries that we use in this project are : 
- ggplot2
- magrittr
- dplyr
- Rtsne
- corrplot
- caret 
- plyr 
- xgboost
- keras 
- Matrix
- glmnet
- tidymodels
- leaps 
- lattice
- keras
- plotrix
- randomForest

# Folders
The repository is organised as follow : 

In the "src" folder, you can find the multiple jupyter notebooks used to reproduce the results. 
In the "data" folder, you can find the training and test data. 
In the "Submissions" folder, you can find the csv files (with the name of the method used) we have submitted on Kaggle. 
In the "Pictures" folder, you can find some images resulting from the jupyter notebook cells. 
You can find the report associated with the project named "Report.pdf". 

# How to reproduce the code ?

The Exploration section of the project is in the "Exploration.ipynb" file.
You can run cells after cells to get the same depicted results. 

The Linear Method section results are in the "Linear_Methods.ipynb" file. It contains the regularization methods (Lasso and Ridge), and the Forward Selection method (which finds the optimal number of predictors). However, the mean of validation errors for Forward Selection method is in the "Regression.ipynb" file under the "Validation for forward selection" section.

The Non Linear Method section is divided in files corresponding to each method : 
- The Neural Network model is in the "Neuronal Network.ipynb" file 
- The Random Forest model is in the "Random_Forest.ipynb" file 
- The Feature Engineering on forward selection model is in the "Regression.ipynb" file
- The Boosting model is in the "Boosting.ipynb" file. 
- The Bagging model is in the "Bagging.ipynb" file. 

In each file, the data is loaded and you can run cells after cell to have the reproducible results. 

# Submissions

You can run the Jupyter Notebook cells right after the "Submission" titles to get our submission files (we re-load the data and clean it). You do not need to run the cross validation steps before.
For example, to get the submission file for Neural Network, you can simply run the cells after "Submission" in the "Neuronal Network.ipynb" file. 
The resulting file will be in the "Submissions" folder.
For final submission, we have chosen the "9_predictors.csv" and "bagging.csv". 
