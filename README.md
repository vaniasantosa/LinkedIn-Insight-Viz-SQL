# LinkedIn-Insight-Viz-SQL
# SQL Project & Data Visualization: LinkedIn Data

## Project Overview
This SQL project harnesses a rich dataset derived from LinkedIn, featuring over 10,000 job postings with detailed attributes across 27 fields including job titles, descriptions, salaries, and locations, along with company-related information. Aimed at delivering insights into job market trends, it supports both job seekers and companies in understanding current demands, compensation, and benefits across industries.

## Database Structure
The database is structured into several key tables:
- **JOB**: Core details of job postings.
- **COMPANY**: Information about companies, including industry and size.
- **JOB_BENEFIT**: Benefits associated with each job.
- **JOB_INDUSTRY**: Industry classifications for job postings.
- **JOB_SKILL**: Skills required for each job.

These tables are linked through primary and foreign keys, allowing for complex queries and analysis.

## Challenges and Solutions
Importing data into SQL presented various challenges:
- **Data Type Mismatches**: Adjusted schema to match source data types.
- **Missing Values**: Employed VLOOKUP for data consistency and removed entries without matching industry data.
- **Data Cleaning**: Utilized Python for preprocessing to ensure data quality.

## Insights and Analysis
The project explores several business questions:
- **Job Skills and Salary**: Identifies high-paying skills and industries.
- **Benefits Trends**: Examines benefits offered across company sizes.
- **Remote vs. On-Site Preferences**: Analyzes trends in job location preferences.
- **Industry Job Posting Traffic**: Highlights active industries based on job posting views.

## Getting Started
1. **Clone the Repository**: Access the complete dataset and SQL scripts.
2. **Database Setup**: Import the SQL database into a management system like MySQL or PostgreSQL.
3. **Explore Queries**: Use the provided SQL queries to uncover insights across different dimensions of the job market.
