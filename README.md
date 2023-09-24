# DS4002Project1
**H2**

**Hypothesis:** The IT, sale, and management skills are the most in demand in the current job market because they have the most frequent appearances in LinkedIn job descriptions and their high associated salary.

**Research Question:** What are the most in-demand skills in the current job market based on LinkedIn job postings in 2023? 

**Model Approach:** We plan on executing first a model for skill frequency, which will require using text analysis to count the amount of times a certain skill appears in the many job descriptions provided in the dataset. We will execute this in two different forms to cross reference. We will perform an analysis using word frequency/count and using entity recognition. We also want to perform linear regression for skill frequency in job descriptions against the salary a skill might produce based on the fact that we define “in-demand” as both frequently requested and high paying. Linear regression will allow us to figure out whether our definition of “in-demand” is valid. The last model we plan to execute, should there be enough time, will be a model predicting what a person’s salary range will be based on the skills they have. This is a type of categorical prediction, which we can create by possibly using a DecisionTree. 

**Executive Summary**: Our models will consist of text analysis, specifically entity recognition, linear regression, and DecisionTree.

**Based on our initial analysis and examination of the dataset of LinkedIn Job Descriptions, the most in demand skills in the job market are IT, sales, and management skills.
The most in-demand skills can be characterized as being the most frequently asked for skills in job postings and pertaining to a job or job title with a high salary.**


**H3: Installing/Building code**

**H3: Usage of code**

**DATA**
[Link to Data](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings)

**Data Dictionary**
| Feature Name  | Description |
| ------------- | ------------- |
| job_id  | Job ID as defined by LinkedIn  |
| description  | Job Description |
| max_salary  | Maximum Salary  |
| med_salary  | Median Salary  |
| min_salary  | Minimum Salary  |
| pay_period  | Pay Period  |
| currency    | Currency of Salary  |
| compensation_type  | Compensation Type  |
| skill_abr  | Abbreviation of skill from the skills CSV  |
| work_type  | Type of Work  |
| title  | Job Title  |
| avg_salary  | Average salary based on given maximum and minimum|

**Summary of Established Dataset:** The data set originally contained eight comma separated value (csv) files. We then reduced this to two CSVs called job_postings and the other called job_skills. Job_postings contained information like salary details, location, and the actual job description as seen on LinkedIn. The job_postings CSV also included 10956 unique job titles, and 13856 unique job descriptions. Job_skills contained a job’s id and an associated skill and its abbreviation. There were 15,886 rows of information with 27 columns. However, there are 128,213 missing values in the job_postings CSV. Of these, the feature with the greatest number of missing values is median_salary. This just means that a new feature will probably have to be created from the remaining and pre-existing values. Some areas of concern were how 41% of the pay_period column had either YEARLY values or another value. However, the remaining 59% were null values. One other column we noted was the work_type column as it had two categories- full_time and contractor -that we decided to combine into one. 


**FIGURES**

**Table of Contents**
| Figures Produced  | Description Summary |
| ------------- | ------------- |
| x  | y  |

**REFERENCES**
