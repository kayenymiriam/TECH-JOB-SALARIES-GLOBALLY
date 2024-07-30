# GLOBAL TECH SALARIES

![](https://github.com/kayenymiriam/TECH-JOB-SALARIES-GLOBALLY/blob/main/Internet%20Computer%20Technology.jpeg)


### INTRODUCTION
This is a Power BI and SQL project on the analysis of employment-related information for employees in the technology industry.

### OBJECTIVES
1. What are the most common job titles in the dataset?
2. How do salaries compare across different job experience levels?
3. Does the average salary vary with company size?
4. Which countries pay the highest average salary for technology-based roles?
5. How have average salaries in the tech industry changed over the years for each job role?
6. Are there differences in the amount of salary paid per employment type?

### SKILLS DEMONSTRATED
Calculated columns, aggregations, subqueries.

### DATA SOURCING
This data was obtained from Kaggle, an online website containing datasets. It contains 607 rows with 11 columns (work year, experience, job title, experience, employment type, salary, salary currency, salary in USD, employee residence, remote ratio, company location, and company size). This data covers the period from 2020 to 2022.

### DATA TRANSFORMATION AND MODELING
This dataset was already cleaned. Data types were changed to whatever was appropriate for each column using Power Query. Three columns were deleted (salary, salary currency, and employee residence). Data was separated into three clusters based on the work year. Relationships were created among them using the job title column since it had unique values.

### ANALYSIS AND VISUALIZATION
1. The 5 most common job titles of the 50 unique job titles in this dataset are: Data Scientist, Data Engineer, Data Analyst, Machine Learning Engineer, and Research Scientist.

2. On which work experience level received the highest average salary:
    - In 2020, mid-level employees had the highest average pay followed by entry-level, experts, and senior-level employees.
    - In 2021, mid-level employees had the highest average pay followed by senior-level, entry-level, and experts.
    - In 2022, expert-level employees had the highest average pay followed by senior-level, mid-level, and entry-level employees.
    - Overall, mid-level employees had the highest average pay followed by experts, entry-level, and senior-level employees.
    However, it should be noted that the dataset contained the most data from mid-level entrants and the least from experts. For example, in 2020, there were only two experts whose salary difference was significantly high. This could explain why experts had a lower average salary compared to mid-level employees in this dataset.
3. On which company size paid the highest average salary:
    - In 2020, large companies paid the highest average salary to their employees followed by small companies and lastly, medium companies.
    - In 2021, large companies paid the highest average salary to their employees followed by small companies and lastly, medium companies.
    - In 2022, large companies paid the highest average salary to their employees followed by medium companies and lastly, small companies.
    - Overall, large companies paid the highest average salary to their employees followed by medium companies and lastly, small companies.
    However, it should be noted that:
    - In 2020 and 2021, the COVID-19 pandemic had a negative impact on most businesses, and many employees were forced to work remotely, which possibly explains why the overall average pay in all companies was the highest in 2021.
    - Smaller companies are usually looking for visibility and often opt to pay more attractive salaries, while medium-sized companies may not yet be well-established and often have more employees and taxes to pay than smaller companies. Large companies are usually well-established and can afford to pay more while effectively managing their expenses. This could explain the variability in pay.
4. On which countries paid the highest average salaries:
    - In 2020, Japan, the United States of America, and New Zealand paid the highest.
    - In 2021, Russia, the United States of America, Canada, and Comoros paid the highest.
    - In 2022, the United States of America, China, Australia, and Canada paid the highest.
    - Overall, Russia, the United States of America, New Zealand, and Japan paid the highest.
    It should be noted that the United States of America has companies that employed more than 50% of the employees in this dataset with an overall average pay of $144,055.26.


5. On employment type:
    - In 2020 and 2021, employees on a contract basis earned significantly more than those who worked full-time and part-time. However, this changed in 2022 as employers paid those employed full-time and part-time significantly more than those on a contract basis. Overall, those paid on a contract basis earned more than their counterparts.
    - Contract jobs often lack job security and extra benefits, so it is probable that in 2020 and 2021, most employers found it safer to employ employees on a contract basis to avoid providing benefits like health insurance during the COVID-19 pandemic. Later, in 2022, there was a significant change, probably due to the fact that most companies had recovered financially.
  
![]
6. On analysis of average salary per job title:
    Of the 50 different job titles, Data Engineers, Data Science Managers, AI Scientists, Data Analysts, Applied Data Scientists, Computer Vision Software Engineers, Data Architects, Data Analytics Managers, Heads of Data Science, Data Engineering Managers, and Principal Data Scientists had an increase in their average salary from 2020 to 2022. 
    Other job titles had unclear trends.
    The highest-paid employees were Financial Analysts in 2021 ($450,000) followed by a Data Analytics Lead in 2022 ($405,000).
    The lowest-paid employees were 3D Computer Vision Researchers in 2021 ($5,409) followed by ML Engineers in 2022 ($10,991).

CONCLUSIONS AND RECOMMENDATIONS
Despite variations in the dataset, the following can be deduced:
- The United States of America offers the most well-paying jobs in the technology field.
- Contract jobs pay more but rarely include allowances.
- Large companies pay more.
- Mid-level and senior-level technology-based jobs are the most popular.
- Data Scientist, Data Engineer, Data Analyst, Machine Learning Engineer, and Research Scientist are the most common job roles in this dataset.
- Data Engineers, Data Science Managers, AI Scientists, Data Analysts, Applied Data Scientists, Computer Vision Software Engineers, Data Architects, Data Analytics Managers, Heads of Data Science, Data Engineering Managers, and Principal Data Scientists had an increase in their average salary from 2020 to 2022.

