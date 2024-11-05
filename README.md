## Survey Data Analysis Project
---

This project contains SQL scripts and datasets used to analyze survey data on respondents’ career aspirations, job preferences, salary expectations, and more. The analysis provides insights into various factors influencing career choices and preferences across demographics, specifically focusing on respondents from India. The goal is to understand the patterns in job aspirations, work environment preferences, salary expectations, and influences on career decisions.

### Project Structure
---

- **Data Cleaning** : Cleaning of Given Raw Data
- **Data Standardization** : Standardization of Cleaned Data
- **Data Analysis** : Analysis of Processed Data/Normalized Data to find some insights about the data.
- **SQL Queries for Analysis**: Solving given question to find insights using sql.
- **Excel Dashboards** : Creation of Different types of Dashboards

### Explanation for each column in the dataset for your reference
---

- **Date**: The date of the survey or data collection.
- **Time**: The exact time the survey response was recorded.
- **Country**: Respondent’s country of residence.
- **Pin Code**: Postal code of the respondent's location.
- **Gender**: Gender of the respondent.
- **Influencing Factors**: Key factors influencing the respondent’s decisions or preferences.
- **Higher Education Abroad**: Whether the respondent is interested in studying abroad.
- **Employment Stability (3 Years)**: The respondent's expectations for job stability over three years.
- **Undefined Mission**: Clarity of the respondent's long-term career mission.
- **Undefined Actions**: Degree of action-taking toward undefined career goals.
- **Company Social Ratings** : Rating Given to company based on their social presence which is 1 to 10.
- **Working Type** : Remote,Hybride,Office.
- **Prefeered Employer** : Challenging,Rewarding, Appreciative.
- **Learning Enviroment** : Self Learning,Expert Learning Program,Observing Other.
- **Career Preferences** : Artificial Intelligence , Busniess Operation , Teaching , Product Manager etc.
- **Prefeered Managment** : Guiding,Supportive,Clear,Demanding.
- **Work Setup** : Work Alone , Work with 2-3 people,5-6 people etc.
- **Work for a Company with Layoff** - Yes,No.
- **Work with one Employer for continue 7 Year** - es,No,Maybe,Depends.
- **Minimum expected Salary**: The lowest salary the respondent expects in a new job.
- **Expected Monthly Salary After 5 Years**: Expected monthly salary after five years of work.
- **Company with No Remote Policy**: Whether the respondent would work for a company without remote work options.
- **Minimum Starting Salary**: The minimum starting salary acceptable to the respondent.
- **Type of Company**: Preferred type of industry or company by the respondent.
- **Work Under Abusive Manager**: Willingness to work under an abusive manager.
- **Daily Working Hours**: Number of hours the respondent expects to work daily.
- **Frequency of Full Week Break for Work-Life Balance**: How often the respondent expects a full week break for balance.

### Busniess Question to Solve for Data Analysis
---
1. What is the gender distribution of respondents from India?
2. What percentage of respondents from India are interested in education abroad and sponsorship?
3. What are the 6 top influences on career aspirations for respondents in India?
4. How do career aspiration influences vary by gender in India?
5. What percentage of respondents are willing to work for a company for at least 3 years?
6. How many respondents prefer to work for socially impactful companies?
7. How does the preference for socially impactful companies vary by gender?
8. What is the distribution of minimum expected salary in the first three years among respondents?
9. What is the expected minimum monthly salary in hand?
10. What percentage of respondents prefer remote working?
11. What is the preferred number of daily work hours?
12. What are the common work frustrations among respondents?
13. How does the need for work-life balance interventions vary by gender?
14. How many respondents are willing to work under an abusive manager?
15. What is the distribution of minimum expected salary after five years?
16. What are the remote working preferences by gender?
17. What are the top work frustrations for each gender?
18. What factors boost work happiness and productivity for respondents?
19. What percentage of respondents need sponsorship for education abroad?


### SQL Queries Question List
---

1. What is the gender distribution of respondents from India?
2. What percentage of respondents from India are interested in education abroad and sponsorship?
3. What are the 6 top influences on career aspirations for respondents in India?
4. How do career aspiration influences vary by gender in India?
5. What percentage of respondents are willing to work for a company for at least 3 years?
6. How many respondents prefer to work for socially impactful companies?
7. How does the preference for socially impactful companies vary by gender?
8. What is the distribution of minimum expected salary in the first three years among respondents?
9. What is the expected minimum monthly salary in hand?
10. What percentage of respondents prefer remote working?
11. What is the preferred number of daily work hours?
12. What are the common work frustrations among respondents?
13. How does the need for work-life balance interventions vary by gender?
14. How many respondents are willing to work under an abusive manager?
15. What is the distribution of minimum expected salary after five years?
16. What are the remote working preferences by gender?
17. What are the top work frustrations for each gender?
18. What factors boost work happiness and productivity for respondents?
19. What percentage of respondents need sponsorship for education abroad?

### Dashboards Information
---
- **Executive Aspiration Dashboard.xlsx**: Dashboard focused on executive career aspirations.
- **Learning Aspiration Dashboard.xlsx**: Dashboard on respondents' learning and educational aspirations.
- **Manager Aspiration Dashboard.xlsx**: Dashboard on managerial career goals of aspirations.
- **Mission Aspiration Dashboard.xlsx** : Dashboard on missions and action of aspiration


### Dashboard 1: **GEN-Z Executive Dashboard**
---
This dashboard summarizes Gen-Z’s career preferences, work preferences, and gender distribution.

1. **Total Respondent**: The total number of survey respondents (Gen-Z individuals) who provided data.
2. **Total Country**: The number of countries represented by the respondents, showing the geographic diversity.
3. **Total Influence Factor**: Number of primary influences on career decisions among respondents.
4. **Career Preference**: Career options preferred by respondents across various fields.
5. **Gen-Z Higher Education**: A bar chart showing the respondents’ inclination towards pursuing higher education abroad, categorized into "Yes," "No," and "Sponsorship Required."
6. **Top 3 Work Setup**: A pie chart displaying preferences for work setups:
   - Working with a team of 5 people.
   - Working with a team of 3 people.
   - Working alone.
7. **Mission and Action Alignment**: A bar chart indicating how many respondents feel aligned or misaligned with their career mission and actions.
8. **Preferred Company**: A chart displaying preferred company types among respondents, including sectors like Tech, BPO, and Operations.
9. **Expected Salary Distribution**: A line chart tracking the expected salary growth among respondents over time.
10. **Gender Distribution**: A pie chart showing the gender breakdown of respondents, with percentages for female, male, and other gender identities.


### Dashboard 2: **Learning Aspiration Dashboard**
---
This dashboard focuses on Gen-Z respondents' aspirations, influencing factors, and preferred working environments.

1. **Work with Employer for 3 Years**: A bar chart displaying respondents' willingness to stay with an employer for at least three years, categorized as "Yes," "No," or "Depends."
2. **Higher Education Aspiration**: A chart that breaks down responses regarding aspirations for higher education abroad, including "Yes," "No," and "Sponsorship Required."
3. **Undefined Mission**: A pie chart showing the percentage of respondents with a clear or unclear career mission, labeled as "Yes" for having a mission and "No" for lacking one.

4. **Influencing Factor**: A bar chart that visualizes the factors most influencing respondents’ decisions, including influences like Parents, People, Social Media, and Friends.
5. **Working Environment**: A chart displaying the preferred work environments, such as:
   - Self-paced work.
   - Learning through expert programs.
   - Observing others.
  
### Dashboard 3: **Mission Aspiration Dashboard** 
---
This dashboard focuses on  respondents' alignment with their career missions and actions, preferred employer characteristics, and overall social ratings of companies.


1. **Mission Alignment**: This pie chart illustrates the percentage of respondents who feel aligned or misaligned with their career mission. The alignment status helps gauge if respondents have a clear sense of purpose in their careers.

2. **Action Alignment**: This section, represented as a pie chart, shows the degree of respondents’ actions toward achieving their career goals. It indicates whether individuals are actively working toward their undefined missions or if they lack initiative.

3. **Employment Stability for 7 Years**: This bar chart explores the respondents' willingness to remain with a company for a seven-year period. The categories range from complete unwillingness (“No”) to a firm commitment (“Will work for 7 years or more”). This data provides insights into job stability expectations among respondents.

4. **Preferred Employer Distribution**: This bar chart visualizes the type of employer environment that respondents prefer. Categories include "Appreciative," "Challenging," "Rewarding," and "Self Learning." It highlights the most desirable traits in a potential employer, with "Challenging" and "Appreciative" environments being particularly favored.

5. **Social Ratings of the Company**: This line chart tracks respondents' social ratings of companies, rated on a scale of 1 to 10. The data shows an upward trend, suggesting that higher social ratings are more common, which may reflect the importance of a company’s social image in attracting employees.

6. **Gender Filter**: The right side of the dashboard features a filter that allows users to segment the data by gender, including categories such as "Female," "Male," "Other," and "Transgender." This enables deeper analysis of how mission alignment, action alignment, and employer preferences vary across gender identities.

### Dashboard 4: **Manager Aspiration Dashboard** 
---
This dashboard provides insights into managerial career aspirations based on survey data, focusing on factors such as gender distribution, salary expectations, working hours, and preferred employer traits.

- **Gender Filter**: Enables filtering of all visuals by gender for focused analysis.
- **Minimum Salary (>3 Years)**: Shows salary expectations of respondents with over three years of experience.
- **Minimum Salary (>5 Years)**: Displays salary expectations for respondents with more than five years of experience.
- **Work Setup**: Illustrates preferred team sizes, highlighting preferences for small to medium-sized teams.
- **Abusive Manager**: Indicates the number of respondents willing to work under an abusive manager.
- **Working Hours**: Visualizes preferred daily working hours, with a strong preference for an 8-hour workday.
- **Preferred Employer**: Displays the type of employer environment respondents favor, with "Challenging" being the most preferred.
