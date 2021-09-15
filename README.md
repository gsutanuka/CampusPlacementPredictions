# Campus Placement Prediction

Often, there is this uncertainty among students about placements. What if there is a way to know your chances of getting placed? This will not only give the students a heads up but will also motivate them to work harder and seek help from teachers and others in time.

In this project, we consider a placement dataset and try to predict whether a candidate will be placed or not based on his/her past records with the help of Machine Learning.

## Problem Statement

1. To do a detailed Exploratory Data Analysis on the data and find out factors that affect and do nor affect in the process of placements.
2. To build ML models that will correctly classify whether a student is placed or not, compare them and find the best model for the classification.

## Data Description

This is a placement data consisting from a certain campus of students pursuing MBA in Marketing and Finance and Marketing and HR.

Number of rows: 215

Number of columns: 15

### Columns:

1.	sl_no -	Serial Number

2.	gender - Gender - Male='M', Female='F'

3.	ssc_p	- Secondary Education percentage- 10th Grade

4.	ssc_b	- Board of Education- Central/ Others

5.	hsc_p	- Higher Secondary Education percentage- 12th Grade

6. hsc_b	- Board of Education- Central/ Others

7. hsc_s	- Specialization in Higher Secondary Education

8. degree_p	- Degree Percentage

9. degree_t - Under Graduation(Degree type)- Field of degree education
10. workex	Work Experience - Yes, No

11. etest_p	- Employability test percentage ( conducted by college)

12. specialisation - Post Graduation(MBA) - Specialization

13. mba_p - MBA percentage

14. status - Status of placement - Placed/Not placed

15. salary -	Salary offered by corporate to the placed candidates 

## Exploratory Data Analysis

1. Does boards of Class 10 and 12 matter?
2. Does work experience matter while getting placed?
3. Is there any gender bias in the process of placements?
4. Does percentage matter for one to get placed?

## Data Preprocessing

1. Dealing with missing values
2. Finding outliers
3. Label Encoding(on binary categorical features)
4. One-hot Encoding(on more than two categorical features)
5. Dropping Unnecessary Columns
6. SMOTE resampling

## Models Used For Classification

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Naive Bayes Classifier
5. Support Vector Machine
6. K-Nearest Neighbors

## Evaluation Metrics

1. Confusion Matrix
2. Performance Matrix for Precision and Accuracy 
3. ROC and AUC

## Packages used

1. Numpy
2. Pandas
3. Statistics
4. Matplotlib
5. Seaborn
6. Sklearn
