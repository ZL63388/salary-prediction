# Salary Prediction

## The Scenario
### Your job as a data scientist is in this assignment is to examine a set of job postings with salaries and then predict salaries for a new set of job postings.

## The Task
### Build a model to predict the salaries for the job postings contained in test_features.csv

## The Dataset
#### test_features.csv - (test data), data shape 1,000,000 rows; 8 columns
##### 1. jobId - multiple various (str)
##### 2. companyId - multiple various (str)
##### 3. jobType - CEO, CTO, CFO, VP, Manager, Senior, Junior, Janitor
##### 4. degree - Doctoral, Masters, Bachelors, High School, None
##### 5. major - Biology, Business, Chemistry, CompSci, Engineering, Literature, Math, None, Physics 
##### 6. industry - Oil, Finance, Web, Health, Auto, Service, Education 
##### 7. yearsExperience - it spans from 0-24 years
##### 8. milesfrommetropolis - it spans from 0-99 miles

#### train_features.csv - (training data), data shape 1,000,000 rows; 9 columns
##### 1. jobId - multiple various (str)
##### 2. companyId - multiple various (str)
##### 3. jobType - CEO, CTO, CFO, VP, Manager, Senior, Junior, Janitor
##### 4. degree - Doctoral, Masters, Bachelors, High School, None
##### 5. major - Biology, Business, Chemistry, CompSci, Engineering, Literature, Math, None, Physics 
##### 6. industry - Oil, Finance, Web, Health, Auto, Service, Education 
##### 7. yearsExperience - it spans from 0-24 years
##### 8. milesfrommetropolis - it spans from 0-99 miles
##### 9. salary - it spans from 0-300 dollars

#### train_salaries.csv - (salaries data), data shape 1,000,000 rows; 2 columns
##### 1. jobId - multiple various (str)
##### 2. companyId - multiple various (str)

## The Models used
### 1. Linear Regression
### 2. Regression Tree
### 3.  Random Forest Regression

## The Results
#### - Linear Regression
##### - r-squared = 0.74
##### - cv_scores = 0.74
##### - adjusted r-squared = 0.74
##### - model intercept = 134.86

#### - Regression Tree
##### - r-squared = 0.46
##### - cv_scores = 0.46
##### - adjusted r-squared = 0.46

#### - Random Forest Regression
##### - r-squared = 0.70
##### - cv_scores = 0.85
##### - adjusted r-squared = 0.75
##### - model intercept = 0.52


### Quick Insights
#### - yearsExperience or the years of experience of a person is the highest correlated variable or the most important factor for one to have a high salary offer
#### - jobType or the type of job a person has also dictates the salary offered. being a CFO or CTO of a company means a higher salary compared to other job types
#### - degree or the degrees completed by a person matters or is one of the factors to have a high salary offer
#### - those who major in business and engineering have a higher salary compared to other majors
#### - oil and finance have the highest salary offers among the industries
