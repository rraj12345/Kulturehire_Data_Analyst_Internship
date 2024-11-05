# Survey Data Analysis Project

This project contains SQL scripts and datasets used to analyze survey data on respondents’ career aspirations, job preferences, salary expectations, and more. The analysis provides insights into various factors influencing career choices and preferences across demographics, specifically focusing on respondents from India. The goal is to understand the patterns in job aspirations, work environment preferences, salary expectations, and influences on career decisions.

## Project Structure

- **SQL Queries for Analysis**: Organized set of SQL scripts performing various analysis tasks.
- **Datasets**:
  - `Normalized DataSet.csv`
    
 ### Explanation for each column in the dataset:

  **Date**: The date of the survey or data collection.
  **Time**: The exact time the survey response was recorded.
  **Country**: Respondent’s country of residence.
  **Pin Code**: Postal code of the respondent's location.
  **Gender**: Gender of the respondent.
  **Influencing Factors**: Key factors influencing the respondent’s decisions or preferences.
  **Higher Education Abroad**: Whether the respondent is interested in studying abroad.
  **Employment Stability (3 Years)**: The respondent's expectations for job stability over three years.
  **Undefined Mission**: Clarity of the respondent's long-term career mission.
  **Undefined Actions**: Degree of action-taking toward undefined career goals.
  **Minimum expected Salary**: The lowest salary the respondent expects in a new job.
  **Expected Monthly Salary After 5 Years**: Expected monthly salary after five years of work.
  **Company with No Remote Policy**: Whether the respondent would work for a company without remote work options.
  **Minimum Starting Salary**: The minimum starting salary acceptable to the respondent.
  **Type of Company**: Preferred type of industry or company by the respondent.
  **Work Under Abusive Manager**: Willingness to work under an abusive manager.
  **Daily Working Hours**: Number of hours the respondent expects to work daily.
  **Frequency of Full Week Break for Work-Life Balance**: How often the respondent expects a full week break for balance.
  **Factors for Productivity and Happiness at Work**: Elements contributing to the respondent’s productivity and happiness at work.
  **What would frustrate you at work?**: Factors that could cause frustration for the respondent at work.

### SQL Queries List

1. **Gender Distribution of Respondents from India**: Analyzes the count of respondents based on gender.
2. **Interest in Higher Education Abroad**: Calculates the percentage of Indian respondents interested in higher education abroad, including those requiring sponsorship.
3. **Top Influences on Career Aspirations**: Lists the top six factors influencing career aspirations among Indian respondents.
4. **Career Aspiration Influences by Gender**: Shows the distribution of influences on career aspirations by gender.
5. **Willingness to Work for 3+ Years**: Calculates the percentage of respondents willing to stay with a company for at least three years.
6. **Socially Impactful Company Preference**: Counts the number of respondents who prefer working for companies with a high social impact.
7. **Social Impact Preferences by Gender**: Breaks down preferences for socially impactful companies by gender.
8. **Minimum Expected Salary Distribution (First 3 Years)**: Analyzes expected salary distribution within the first three years of employment.
9. **Expected Monthly Salary After Five Years**: Lists expected salary distribution after five years.
10. **Remote Work Preferences**: Calculates the percentage of respondents who prefer remote work.
11. **Preferred Daily Work Hours**: Shows the most common daily work hours.
12. **Work Frustrations**: Lists common work frustrations.
13. **Need for Work-Life Balance by Gender**: Shows the need for work-life balance interventions, broken down by gender.
14. **Willingness to Work Under Abusive Manager**: Counts respondents willing to work under an abusive manager.
15. **Minimum Expected Salary After Five Years**: Similar to (9), but focused on specific distribution insights.
16. **Remote Working Preferences by Gender**: Lists remote work preferences, broken down by gender.
17. **Top Work Frustrations by Gender**: Analyzes top work frustrations for each gender.
18. **Factors That Boost Work Happiness and Productivity**: Lists the factors that respondents feel boost their happiness and productivity at work.
19. **Sponsorship Requirement for Higher Education**: Calculates the percentage of respondents needing sponsorship for education abroad.

### Datasets Information

- **Executive Aspiration Dashboard.xlsx**: Dataset focused on executive career aspirations.
- **Learning Aspiration Dashboard.xlsx**: Data on respondents' learning and educational aspirations.
- **Manager Aspiration Dashboard.xlsx**: Survey data on managerial career goals and aspirations.
- **Normalized DataSet.csv**: A normalized version of the data, formatted for easier analysis.

## Requirements

- SQL Database (compatible with the SQL queries provided, e.g., MySQL, PostgreSQL)
- Excel-compatible software (Microsoft Excel, Google Sheets) to view `.xlsx` files
- Python or R (optional) for any additional data wrangling if required


This README provides an overview and setup instructions to help users navigate and understand the project. Let me know if there’s anything more specific you’d like to add!
