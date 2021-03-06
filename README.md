# StackOverflow Developer Survey Analysis 2020

## File Descriptions
- <b>Jupyter Notebook</b> 
1. StackOverFlow-Survey-Analysis.ipynb -> Contains the code for Exploratory Data Analysis
- <b>Dataset</b> 
1. developer_survey_2020/survey_results_public.csv -> Contains the responses given against the survey questions, compiled under respective fields
2. developer_survey_2020/survey_results_schema.csv -> Defines the schema of the `survey_results_public` file and what each field denotes

## Motivation

An exploratory analysis of Stackoverflow's Developer Survey 2020 data using the CRISP-DM process to infer the trends from the responses given by various developers to the survey

## Business Understanding

1. What factors influence the Job Satisfaction of Male and Female developers?
2. What factors influence the Job Satisfaction of developers in a Developed (United States) vs Developing (India) country?
3. What are the compensation trends across countries?
4. How many hours do developers work across countries?
5. What factors cause the developers to look for new jobs in a Developed (United States) vs Developing (India) country?

## Data Understanding

- ~70% respondents have said they are developers
- ~70% respondents have said they are employed full time
- ~20% respondents that are full time developers also consider it as a hobby
- ~75% of the full time developers identify themselves as Male, 15% as Female and the remaining as non-binary
- Majority of the respondents lie between the ages of 20-40


## Evaluating Results

A concise writeup of the evaluation and analysis can be found here https://abhi-rohatgi.medium.com/stackoverflow-developers-of-2020-have-their-say-191c60de42f8

## Packages Used
- Pandas
- Matplotlib
- Seaborn

## Acknowledgement
StackOverflow Survey Data 2020 [https://insights.stackoverflow.com/survey]
Seaborn Violin Plot [https://medium.com/analytics-vidhya/violin-plot-in-a-nutshell-ecd5ed0abcff]
