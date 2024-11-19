1. Overview
This section provides a brief description of the project, explaining the goal of the repository: cleaning and analyzing layoffs data from various companies. It highlights the two main processes involved: data cleaning and exploratory data analysis (EDA).

2. Data Cleaning
This section outlines the steps taken to clean the data before analysis:

Remove Duplicates: It shows how duplicates in the data are identified and removed using SQL queries with window functions like row_number() to partition the data based on relevant columns (e.g., company, location, layoffs).

Handle Missing and Null Values: Describes how missing values, empty strings, and rows with null values are cleaned or deleted to ensure the dataset is accurate and complete.

Standardize Data: This part explains the steps to ensure consistency in the data, like trimming whitespace from company names, fixing country names, and converting dates into a consistent format.

Remove Unnecessary Columns: After cleaning, it removes temporary columns (e.g., row_num) used for intermediate processing.

3. Exploratory Data Analysis (EDA)
In this section, the process of exploring the cleaned data to gain insights is described:

General Overview of the Data: Basic queries that help understand the structure of the cleaned data, like checking maximum values or filtering for specific data points (e.g., companies with 100% layoffs).

Grouping and Aggregating Data: This part focuses on aggregating the data to find trends, such as total layoffs by company, industry, or stage of layoffs.

Temporal Analysis: Analyzes layoffs data over time, such as total layoffs per month and rolling totals.

Ranking Companies by Layoffs: Explains how companies are ranked based on the number of layoffs they reported each year.

4. Summary of Key Data Cleaning Steps
This section summarizes the main actions performed during the data cleaning process:

Removing duplicates.
Standardizing and formatting data.
Handling missing or invalid data.
Dropping unnecessary columns.
