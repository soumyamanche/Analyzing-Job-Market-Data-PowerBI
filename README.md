# Analyzing Job Market Data in Power BI

A Power BI project analyzing data science job market data to understand job postings, salaries, experience levels, job titles, and in-demand skills.

## Dashboard

### Job Level Analysis

![Job Level Analysis](imgs/job-level-analysis.png)

### Job Titles

![Job Titles](imgs/job-titles.png)

### Salary Analysis

![Salary Analysis](imgs/salary-analysis.png)

### Skill Analysis

![Skill Analysis](imgs/skill-analysis.png)

### Skill Likelihood

![Skill Likelihood](imgs/Skill%20Likelihood.png)

## What I Analyzed

- Job postings by experience level
- Job posting trends over time
- Job titles and job demand
- Salary ranges and average pay
- Salary vs. years of experience
- Skills required across job postings
- Skill demand and trends over time
- Company and industry information

## Data Preparation

Used Power Query to:

- Clean and transform the job posting data
- Handle missing and inconsistent values
- Prepare job skills for analysis
- Split skills into individual rows
- Standardize skill names such as `power_bi` and `powerbi`

## DAX

Created measures and calculations to analyze:

- Posting Count
- Skill Count
- Average Pay
- % Skill in Posting
- Salary and experience relationships

## Tools Used

- Power BI
- Power Query
- DAX
- Data Visualization

## Project Source

This project was completed as part of a **DataCamp case study** on analyzing job market data.

## Repository Structure

```text
Analyzing-Job-Market-Data-PowerBI
│
├── PowerBI
│   └── Job_Market_Analysis.pbix
│
├── Dataset
│   └── job_postings.csv
│
├── imgs
│   ├── job-level-analysis.png
│   ├── job-titles.png
│   ├── salary-analysis.png
│   ├── Skill Likelihood.png
│   └── skill-analysis.png
│
└── README.md
```