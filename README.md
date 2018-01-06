# PML -- Yuling Tu @ 01/05/2018 
## Coursera Practical Machine Learning Course

This repository was created for Coursea Practical Machine Learning course project.  

## Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

## Data

The training data for this project are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


The data for this project come from this source: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har. 

Special thanks to the following authors for being so generous in sharing their data for public usage.

Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.

## Project Goal

The goal of this project is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. A report is created using R Markdown software, and the corresponding files are included in this repository.  

The report describe the process of data cleaning, model building, cross validation testing.  It also including the model selection process, out-of-sample error and variable importance.  Few charts are included to explain why the model selected is the best fit.  Finally, the report will also use the final prediction model to predict 20 different test cases.
