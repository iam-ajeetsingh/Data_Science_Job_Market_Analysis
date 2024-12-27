# Job Market Analysis using Web Scraping: Data Science Jobs in India

This project analyzes the job market for data science positions in India, providing insights into job opportunities, required skills, and trends in the field. The analysis is based on data collected from the job portal [Indeed India](https://www.in.indeed.com) using web scraping techniques.

## Project Overview

The goal of this project is to:
- Understand the current state of the data science job market in India.
- Identify key skills and qualifications required for data science roles.
- Highlight trends in job locations, job types, and job titles.

## Methodology

### Data Collection
- **Source**: [Indeed India](https://www.in.indeed.com)
- **Sample Size**: 150 job postings for the "Data Scientist" position in India.
- **Tools Used**: 
  - `selenium` library for web scraping.
  - Data was scraped from the first 10 pages of search results, with each page containing 15 job postings.
- **Data Collected**: Job title, location, job type, and key skills required.

### Data Analysis
- **Libraries Used**: 
  - `pandas`, `numpy` for data cleaning and preprocessing.
  - `matplotlib`, `seaborn` for data visualization.
- **Analysis Performed**:
  - Job location distribution.
  - Job type distribution (Full-time, Part-time, Temporary).
  - Key skills and qualifications required.
  - Trends in job titles.

## Key Findings

1. **Job Locations**:
   - Bangalore has the highest number of job openings (34% of total).
   - Hyderabad (11%) and Remote jobs (8%) follow as the next most common categories.

2. **Job Types**:
   - ~85% of the job openings are Full-time positions.
   - Temporary, Part-time, and Fresher roles are mostly remote-based.

3. **Job Titles**:
   - 25% of the job postings are for the title "Data Scientist."
   - Other common titles include "Staff Engineer," "AI/ML Engineer," and "Lead Data Scientist."

4. **Required Skills**:
   - Proficiency in programming languages: Python, R, Java.
   - Experience with big data technologies: Hadoop, Spark.
   - Knowledge of machine learning algorithms: regression analysis, decision trees.
   - Database technologies: SQL, NoSQL.
   - Strong communication skills.
