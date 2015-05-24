---
output: html_document
---
# Practical Machine Learning - Course Project
## Introduction
The goal of this project is to analyze the Weight Lifting Excercise dataset obtained from the HAR(Human Activity Recognition) Website and pick the best model selection algorithm to predict the class of excercises that are best performed by the person wearing the activity mearsuning device. The data was collected for six persons performing a pre-determined set of excersices which were classified into five groups as listed here.

* Class A - done exactly accoring to specification
* Class B - throwing the elbows to the front
* Class C - lifting the dumbell only halfway
* Class D - lowering the dumbell only halfway
* Class E - throwing the hips to the front

The training and test dataset provided at the website had the following dimensions

* Training dataset - 19622 observations & 160 variables
* Test dataset - 20 observations & 160 variables

The data is pre-processed to eliminate variables that do not contribute towards the model prediction followed by model selection.

## Note of Caution
We would like to give a heads up that if you plan to run the R-markdown submitted as part of this project it will take a few minutes for the whole process to complete. In this project 3 model selection algorithms were considered and the whole process may take anywhere between 8 to 15 minutes.

## Data Pre-Processing
The data was pre-processed to eliminate variables that had over 90% missing or *NA* values. Also eliminated were variables that were not relevant to the prediction analysis or were highly co-related.

## Model Selection
The cleaned training data was sliced into model training and validation datasets. Three model selection algorithms were considered for the prediction analysis and they are as follows.

* Regression Tree(rpart from caret package)
* Random Forest(randomForest from randomForest package)
* Gradient Boosting(gbm from caret package)

## Submission
The following files were submitted as part of the course project.

* PrcaticalMachineLearningProject.Rmd
* PracticalMachineLearningProject.html
* PracticalMachineLearningProject.pdf
* Readme.md

I have submitted both the *PDF* and *HTML* versions of the knitr generated documents in case there is an issue looking at HTML document please look at PDF version of the document.

