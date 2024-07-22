# STAT 636 End of Semester Project

## Background
This project is completed as an end of semester project for a class in the MS in Statistics program at Texas A&M University. 

## Data
Source: https://doi.org//10.24432/C5MC89

This dataset was created by the University of California (UC), Irvine Machine Learning Repository (Realinho and Baptista, 2021). In this dataset, information from 4424 undergraduate students are compiled from several disjoint databases. A total of 36 features are included in the data such as information that is known during the time of student enrollment (e.g., demographics and social-economic factors) as well as their academic performances at the end of their first two semesters. This dataset is part of a project focusing on contributions to reducing academic dropout and failure in higher education.


## Project Description
The goal of our project is to find the best classification model to predict the student’s dropout or non- dropout status in a higher education institution. Initially, we split the dataset into a training set and testing set. The training set contains 80% of the students while the latter contains 20%. We then implement the following five methods separately to the data: linear discriminant analysis (LDA), quadratic discriminant analysis (QDA), logistic regression, naive Bayes, and KNN (packages: MASS, e1071, and class). We chose these methods to compare for our project since they are all common and popular choices for classification purposes. After implementing each method, we calculated the test error of each method and used a bar graph to depict the test errors (package: ggplot2). If the method has the smallest test error than the other methods, we determine that method to have the best performance. LDA and logistic regression have the smallest test error of 0.15 while KNN had the largest of 0.26. For future purposes, it might be of value to adjust the LDA threshold and try different thresholds to see if the test error changes drastically. It also could be insightful to test KNN again with larger set K-values.
