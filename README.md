Student Performance Prediction 

#### Life cycle of the Machine learning Project

- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- Exploratory data analysis
- Data Pre-Processing
- Model Training
- Choose best model
- Rest API for Model
- Application for ML Model
- Deploy model on AWS using AWS Beanstalk and CodePipeline

### Problem statement
This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

### Data Collection
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

### Dataset Information
- gender : sex of students  -> (Male/female) {category variable}
- race/ethnicity : ethnicity of students -> (Group A, B,C, D,E) {category variable}
- parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school) {category variable}
- lunch : having lunch before test (standard or free/reduced) {category variable}
- test preparation course : complete or not complete before test {category variable}
- math score {int}
- reading score {int}
- writing score {int}


