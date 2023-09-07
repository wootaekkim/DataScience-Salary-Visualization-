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
#### Job Category in the Data
- This section displays the distribution of samples across various job categories (Analyst, Data Scientist, Data Engineer, Developer/Researcher).<br />
- It also shows the categorization of position titles within each job category and the number of samples for each position title.<br />
#### Avg. Salary by Job Category and Country
- This section presents the average salary for all data science jobs in the dataset, as well as the average salary for each specific job category.<br />
- Additionally, it provides a visual representation of how the average salary for data science jobs has evolved over the years.<br />
- Users can delve into country-specific data by clicking on individual countries on the map. This action reveals the average salary for data science jobs in that country, along with the average salary for each job category within that country.<br />
#### Remote Ratio and Salary
- This section illustrates how average salary is affected by different remote work ratios for each job category.<br />
- Additionally, a pie chart provides the proportion of each remote work ratio in the total dataset, indicating the prevalence of remote, hybrid, and on-site positions.<br />
- Filters for company size and year allow users to explore the data for different company sizes and across different years.<br />
#### Experience Level and Salary
- This section explores salary variations based on experience levels.<br />
- By clicking on points within the line chart, users can compare average salaries among different job categories within the same experience level.<br />
- This interaction also provides insight into the percentage of each job category relative to the total number of positions within each experience level in our dataset.<br />
- For a more in-depth analysis of salary trends within specific job categories, users can utilize the job category filter to narrow their focus.<br />
#### Company Size and Salary
- This section presents how salary varies based on company size.<br />
- On the top left, a pie chart illustrates the proportion of job positions from various company sizes compared to the total number of positions in our dataset.<br />
- On the right, a bar chart displays the percentage of job positions for each category relative to the total number of positions in different company size categories within our dataset.<br />
- To delve deeper into salary trends for specific job categories and years, users can utilize filters for job category and work year, enabling more focused exploration.<br />

To access and interact with the full Tableau dashboard, please click on the provided [Tableau Dashboard Link](https://public.tableau.com/views/DataSciencJobsSalarySummary/DataScienceJobsSalarySummary?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) <br />
<br />
This comprehensive dashboard offers a detailed and user-friendly way to understand and analyze the data science salary dataset, enabling users to explore salary trends, job categories, experience levels, remote work ratios, and other relevant factors that impact salaries within the data science field.
