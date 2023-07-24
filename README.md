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
This was done using Python. The main task was to convert strings in more readable form such that when I made them into visualization, it is mush more readable for other.
Columns that I made alteration include experience_level, employment_type, employee_residence, company_location. I changed abbreviations to full text for experience level and employment type. Then for employee_residence and company_location columns, I converted from country code to country name. Transformed data is included above as **ds_salary_tableau.csv**.<br /> 
Other than data manipulation, some exploration of data is also included in **2023 data science salary data manipulation for tableau.ipynb** file incuded above. data exploration includes checking missing values, categorizing columns into qualitative and quantitative variables, data type of each columns, and checking total number of data.  

### Data Visualization using Tableau
Dashboard was created using tableau. This consists of four Dashboards; Position title and Job Category, By Remote Ratio, By Experience Level, and Overall Trend. Click below to go to the dashboard in Tableau Public. <br />
[Tableau Dashboard Link](https://public.tableau.com/views/SummaryofDataScienceSalary/TrendofAvg_Salary?:language=en-US&:display_count=n&:origin=viz_share_link) <br />
<br />
**Position title and Job Category**<br />
This dashboard maninly shows how many samples were in each Job category (Analyst, Data Scientist, Data engineer, Developer/Researcher). <br />
Furthermore, this also shows which position title was categorized in which category and number of samples with each position title.<br />
<br />
**By Remote Ratio**<br />
Here, dashboards mainly shows how salary changes by each would remote ratio would affect salary for each job category. <br />
I also have included pie chart showing proportion of each remote ratio out of total data. Assuming that this is randomly sampled, this show how much of total positions are remote( remote ratio =100), hybrid(remote ratio = 50), and on-site(remote ratio = 0). Company size and year filter has been added to thid dashboard so that people can explore for different company sizes and each year. <br/>
<br />
**By Experience Level**<br />
This dashboard shows how salary changes by eperience level. Here we can see how average salary foe each experience level changes over the years, average salary for each job category at each experience level, and proportion of each experience level in each job category. In terms of pie chart, size of each pie chart show sample size with each job category. Job category and compnay size filters were added for further exploration and closer look for different company size and each job category. <br />
<br />
**Overall Trend**<br />
Here I tried to show overall average data science salary. I have show trend of average salary for each job category over the years and overall average salary of each job category. Moreover, average datascience salary in different countries and table showing average salary under various factors (company size, contract, job category, experience level) are included for closer look of the data. For map and table, job category filter is added so that people can explore average salary for different job category.<br />
<br />

