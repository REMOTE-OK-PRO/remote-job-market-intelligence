

RemoteOK Job Market Analysis (TEAM A Mini Project)
## Project Overview
This project focuses on scraping, cleaning, and analyzing remote job listings from RemoteOK using
Python. The goal is to extract insights related to job demand, job types, locations, and posting
trends over time, while following ethical scraping practices.
## Tech Stack & Tools
Python, Selenium, BeautifulSoup, Pandas, Matplotlib
## Project Structure
TEAM_A_miniproject.py – Scraping script
visualization.py – Visualization script
remoteok_jobs.csv – Raw data
remoteok_jobs_cleaned.csv – Cleaned data
visuals/ – Generated charts
## Scraping Process
The scraper uses Selenium to dynamically load job listings from multiple categories and extracts
job title, company name, job type, location, date posted, job URL, and skills when available.
## Data Cleaning
Duplicate entries were removed, invalid locations filtered, and relative date values were converted
into actual posting dates.
Important Note on Skills Data
RemoteOK does not consistently provide skills for all jobs. Therefore, two approaches were
considered:
- Skip skill-based charts (safe and ethical).
- Infer skills from job titles (used only if allowed).
## Visualizations
Top Job Titles, Job Type Distribution, Top Locations, Jobs Posted Over Time, and optional inferred
skills charts.
## Conclusion
This project demonstrates an end-to-end data pipeline from scraping to visualization while
maintaining ethical standards and transparency.