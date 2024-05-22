# Data Mining Investigation

## Description
This is an investigation into job titles. My domain knowledge of job title selection and its impact on email sales prospecting was the driver for this project. The literature review confirmed my hypothesis that job titles have an impact. I utilized my experience with Google Sheets, CSV files, and Excel formulas & pivot tables to prepare the data and complete the data transformations.

## Data Preparation Steps Completed
- Data Cleaning – pre-assembly (deleted extra columns)
- Data Integration – external CSV files
- Data Cleaning – duplicate rows, job titles
- Data Selection – SQL in Athena – internal data set (job titles & locations)
- Data Cleaning – internal data set

## Tools Used
- Amazon Athena
- Google Sheets
- Microsoft Excel

## Techniques Applied
- Data Cleaning – multiple rounds, formulas used
- Data Integration
- Data Selection/Querying
- Data Transformation – pivot tables, charts

## Main Questions Asked and Answers
What is the most common job title (in the data set)?
President, followed by Vice President, and then Director (these are the full titles, the department specific versions were not as popular, ex. Vice President of Engineering)

Do job titles vary by region?
Yes, but not significantly. The top 10 job titles from the United States only view were all within the top 20 most common titles in the overall view, but in different spots.

What job titles are most frequent within different industries?
I created drilled down views for this question of the top 20 most common job titles in the top 3 overall most common industries within the external data set.

Are general job titles more popular than department specific titles?
Yes, the four most common job titles overall are general titles with the first department title being CEO. The top 4 job titles were President, Vice President, Director, and Managing Director




