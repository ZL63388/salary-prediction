# Salary Prediction

### The Scenario
#### Your job as a data scientist is in this assignment is to examine a set of job postings with salaries and then predict salaries for a new set of job postings.

### The Task
#### Build a model to predict the salaries for the job postings contained in test_features.csv

## The Dataset
##### test_features.csv - test data
###### jobId - multiple various (str)
###### companyId - multiple various (str)
###### jobType - CEO, CTO, CFO, VP, Manager, Senior, Junior, Janitor
###### degree - Doctoral, Masters, Bachelors, High School, None
###### major - Biology, Business, Chemistry, CompSci, Engineering, Literature, Math, None, Physics 
###### industry - Oil, Finance, Web, Health, Auto, Service, Education 
###### yearsExperience - it spans from 0-24 years
###### milesfrommetropolis - it spans from 0-99 miles

##### train_features.csv - training data
###### jobId - multiple various (str)
###### companyId - multiple various (str)
###### jobType - CEO, CTO, CFO, VP, Manager, Senior, Junior, Janitor
###### degree - Doctoral, Masters, Bachelors, High School, None
###### major - Biology, Business, Chemistry, CompSci, Engineering, Literature, Math, None, Physics 
###### industry - Oil, Finance, Web, Health, Auto, Service, Education 
###### yearsExperience - it spans from 0-24 years
###### milesfrommetropolis - it spans from 0-99 miles
###### salary - it spans from 0-300 dollars

##### train_salaries.csv - salaries data
###### jobId - multiple various (str)
###### companyId - multiple various (str)

### The Models used
#### Linear Regression
#### Regression Tree
#### Random Forest Regression

### The Results
#### Linear Regression
##### r-squared = 0.74
##### cv_scores = 0.74
##### adjusted r-squared = 0.74
##### model intercept = 134.86

#### Regression Tree
##### r-squared = 0.46
##### cv_scores = 0.46
##### adjusted r-squared = 0.46

#### Random Forest Regression
##### r-squared = 0.70
##### cv_scores = 0.85
##### adjusted r-squared = 0.75
##### model intercept = 0.52


### Quick Insights
#### yearsExperience or the years of experience of a person is the highest correlation or factor for one to have a high salary offer
#### jobType or the type of job a person has also dictates the salary offered. being a CFO or CTO of a company means a higher salary compared to other job types
#### degree or the degrees completed by a person matters or is one of the factors to have a high salary offer
#### those who major in business and engineering have a higher salary compared to other majors
#### oil and finance have the highest salary offers among the industries
