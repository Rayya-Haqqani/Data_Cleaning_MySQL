### Data Cleaning and Exploratory Data Analysis (EDA)

This project involves a comprehensive data cleaning process to prepare the dataset for analysis while ensuring the integrity and quality of the data. The key steps include:

- **Creating a Staging Table**: Establishing a staging table to store cleaned data, allowing access to the original raw data if needed.
- **Removing Duplicates**: Identifying and eliminating duplicate records to ensure each entry is unique.
- **Standardizing the Data**: Converting text to a consistent format, such as making all entries lowercase and trimming excess spaces.
- **Removing NULL Values or Blank Spaces**: Eliminating rows with `NULL` values or blank spaces to maintain data integrity.
- **Removing Unnecessary Rows or Columns**: Deleting rows or columns that do not contribute to the analysis, simplifying the dataset for effective analysis.

In addition, the project employs Common Table Expressions (CTEs) and various SQL techniques for exploratory data analysis (EDA) on the layoffs dataset. The key analyses performed include:

1. **Dataset Overview and Maximum Values**: Retrieving the entire dataset and calculating the highest total layoffs and layoff percentages.
2. **Total Layoffs by Company and Industry**: Aggregating total layoffs by company and industry to identify the most affected sectors.
3. **Layoff Trends Over Time**: Calculating total layoffs by year and month to provide insights into trends over time.
4. **Top Companies by Year**: Ranking the top five companies with the highest layoffs for each year, highlighting those most impacted.
