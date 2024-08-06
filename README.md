# Snowflake Unicorn Companies Analysis

Project Overview
This project involves analyzing data from the unicorn companies dataset to provide insights into various aspects such as industry valuation, company performance, and geographic distribution of high-value companies. The analysis is performed using SQL queries in Snowflake, focusing on cleaning the data and answering business-related questions.

Source dataset: https://www.kaggle.com/datasets/deepcontractor/unicorn-companies-dataset

## Data

The dataset used for this analysis provides detailed information about unicorn companies. It includes features such as company name, valuation, funding amount, sector, industry, founding year, and headquarters location. This data captures key aspects of unicorn companies and their growth trajectories.

## Analysis

The project performs the following analysis steps:

**Data Cleaning:**
   - Handling missing values
   - Converting data types
   - Data transformations

**Analyzing Data:**
   - SQL scripts provide answers to the following busienss questions:
       - What is the average company valuation for each industry? How do these industries rank based on their average valuation?
       - Which industry has the highest total raised?
       - Which are the top 10 cities in the United States with the highest average company valuation? How many companies are there in each of these cities?
       - What are the top companies in each industry based on the total amount raised, and how do they rank within their industry?
       - Which are the top 3 companies by valuation within each industry? What is their valuation relative to the average valuation in their industry?
       - What is the correlation between total raised and valuation by country? Calculated for top countries by number of comapnies (HAVING COUNT(*) > x)?
