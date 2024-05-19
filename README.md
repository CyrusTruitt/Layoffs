
# Layoffs


## Explanation

In this project, I am showcasing essential data analysis skills, including data cleaning and preprocessing, such as importing raw datasets into MySQL, removing duplicates, standardizing data, handling missing values, and removing unnecessary columns and rows. I have conducted exploratory data analysis to uncover key insights, identifying trends and patterns in layoffs across companies, industries, and countries, and analyzing layoffs over time. I've enhance my SQL and database management skills by writing and executing queries for data manipulation and extraction. This project was executed to help develop my critical thinking and problem-solving abilities by making informed decisions about data handling and interpreting data to generate actionable insights. Additionally, I have improved my documentation and communication skills by summarizing and presenting my findings clearly and concisely, supported by data-driven evidence. Through this hands-on experience with real-world data, I have enhanced my technical skills and ability to derive valuable insights from complex datasets.



### Data Cleaning | Steps Followed

- Step 1 : Import RAW dataset into MySQL.
- Step 2 : Removed all duplicates from dataset 
- Step 3 : Standardize data
    - updated all crypto related industry names to 'crypto'
    - updated "United States." -> "United States"
    - changed 'date' format
    - formated 'date' column from a 'text' column to 'date'
- Step 4 : Get Rid of Null and Blank Values
    -  Taking a look at the data, I was not able to populate the NULL values under 'total_laid_off' and 'percentage_laid_off' because I don't have 	the company total.  if I had the company total I would be able to do calculations for example: 
	 The company had 50 employees and 100% were laid off, I could populate the 'total_laid_off' by saying "If this is 50, and 100% were laid 	off, then 50 people were laid off". We weren't supplied with that data so it's impossible to come to populate the column.
- Step 5 : Remove unnecessary columns and Rows 

### Exploratory Data Analysis | Steps Followed 

- Step 1: Found which company had the most layoffs
    - Amazon had the most layoffs out of any company with 18,150
- Step 2: Found which industry was hit with the most amount of layoffs
    - The consumer industry had the most layoffs with 44,782
- Step 3: Found which country had the most layoffs
    - United States had the most layoffs with 256,559
- Step 4: Found the amount of layoffs that happened within the years 2020-2023
    - 2022 was the worst year with 160,661 layoffs
- Step 5: Found the amount of laid off employees by stage of the company
- Step 6: Found the rolling total of layoffs
    - 'total_off' represents how many people were laid off each month and 'rolling_total' represents a month to month progression of the total amount 	of people laid off
    - From march of 2020 to march of 2023, 383,159 people lost their jobs.
- Step 7: Found who laid off the most people per year
    - 2020: Uber had the biggest layoff with 7,525

	- 2021: Bytedance had the biggest layoff with 3600

	- 2022: Meta had the biggest layoff with 11,000

	- 2023: Google had the biggest layoff with 12,000

   











