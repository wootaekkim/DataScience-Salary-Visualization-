# DataScience-Salary-Visualization-

Then main goal of this project was to create dashboard summarizing the 2023 Data Science Salary data from Kaggle (https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023).<br />
Columns of this data is shown below: <br />
<br />
1. work_year: The year the salary was paid.<br />
2. experience_level: The experience level in the job during the year<br />
3. employment_type: The type of employment for the role<br />
4. job_title: The role worked in during the year.<br />
5. salary: The total gross salary amount paid.<br />
6. salary_currency: The currency of the salary paid as an ISO 4217 currency code.<br />
7. salaryinusd: The salary in USD<br />
8. employee_residence: Employee's primary country of residence in during the work year as an ISO 3166 country code.<br />
9. remote_ratio: The overall amount of work done remotely<br />
10. company_location: The country of the employer's main office or contracting branch<br />
11. company_size: The median number of people that worked for the company during the year<br />
<br />

### Data Manipulation 
In this project, I utilized Python for data manipulation to enhance the readability of the dataset, which was later used for data visualization in Tableau. The primary objective was to improve the dataset's visual presentation for others. The following columns were modified to achieve this: experience_level, employment_type, employee_residence, and company_location. Abbreviations in experience level and employment type were converted to full text, while country codes in employee_residence and company_location were transformed into country names. The transformed data has been saved in the file named "ds_salary_tableau.csv." 

### Data Exploration
Before proceeding with data visualization, I conducted data exploration in the "2023 data science salary data manipulation for tableau.ipynb" notebook. This exploration involved:<br />
- Checking for Missing Values: Ensuring that the dataset is complete and no crucial data is missing.<br />
- Categorizing Columns: Identifying qualitative and quantitative variables for a better understanding of the data's characteristics.<br />
- Data Type Check: Verifying the data type of each column to ensure appropriate data handling.<br />
- Total Data Overview: Determining the total number of data points available for analysis.<br />

### Data Visualization using Tableau
For data visualization, I created an interactive dashboard using Tableau, comprising four main sections Click below to go to the dashboard in Tableau Public. <br />
<br />
**Position title and Job Category** <br />
- This section displays the distribution of samples across various job categories (Analyst, Data Scientist, Data Engineer, Developer/Researcher).<br />
- It also shows the categorization of position titles within each job category and the number of samples for each position title.<br />
<br />
**By Remote Ratio** <br />
- This section illustrates how salary is affected by different remote work ratios for each job category.<br />
- Additionally, a pie chart provides the proportion of each remote work ratio in the total dataset, indicating the prevalence of remote, hybrid, and on-site positions.<br />
- Filters for company size and year allow users to explore the data for different company sizes and across different years.<br />
<br />
**By Experience Level** <br />
- section presents how salary varies based on experience level.<br />
- Users can observe the average salary for each experience level over the years, average salary for each job category at different experience levels, and the proportion of each experience level within each job category.<br />
- Pie charts show the sample size for each job category, offering insights into the data distribution.<br />
- Filters for job category and company size facilitate closer examination of salary trends for specific job categories and company sizes.<br />
<br />
**Overall Trend** <br />
- Here, I showcase the overall average data science salary trends.<br />
- Users can explore the trend of average salary for each job category over the years, as well as the overall average salary for each job category.
The visualization includes average data science salaries across different countries, and a table presenting average salaries based on various factors such as company size, contract type, job category, and experience level.<br />
- A job category filter allows users to focus on the salary trends for different job categories.<br />
<br />

To access and interact with the full Tableau dashboard, please click on the provided [Tableau Dashboard Link](https://public.tableau.com/views/SummaryofDataScienceSalary/TrendofAvg_Salary?:language=en-US&:display_count=n&:origin=viz_share_link) <br />
<br />

This comprehensive dashboard offers a detailed and user-friendly way to understand and analyze the data science salary dataset, enabling users to explore salary trends, job categories, experience levels, remote work ratios, and other relevant factors that impact salaries within the data science field.
