### Data Cleaning and Exploratory Data Analysis (EDA)

This project focuses on preparing a dataset for analysis through a meticulous data cleaning process that upholds data integrity and quality. The main steps taken are:

- **Staging Table Creation**: A staging table is created to hold cleaned data, allowing for easy access to the original raw data when necessary.
- **Duplicate Removal**: Duplicate entries are identified and removed to ensure the uniqueness of each record in the dataset.
- **Data Standardization**: Text data is standardized by converting all entries to lowercase and eliminating extra spaces for consistency.
- **NULL and Blank Value Removal**: Rows with `NULL` values or blank spaces are discarded to maintain the dataset's integrity.
- **Unnecessary Data Elimination**: Any rows or columns that do not aid the analysis are removed, streamlining the dataset for more effective exploration.

Moreover, the project leverages Common Table Expressions (CTEs) and various SQL techniques to conduct exploratory data analysis (EDA) on the layoffs dataset. The analyses performed encompass:

1. **Complete Dataset Review and Maximum Metrics**: Accessing the entire dataset and determining the highest values for total layoffs and layoff percentages.
2. **Layoffs by Company and Industry**: Summarizing total layoffs across companies and industries to pinpoint the most impacted sectors.
3. **Trends Over Time**: Analyzing total layoffs on a yearly and monthly basis to uncover trends in layoffs.
4. **Leading Companies by Year**: Identifying the top five companies with the highest layoffs for each year, showcasing the most affected organizations.
