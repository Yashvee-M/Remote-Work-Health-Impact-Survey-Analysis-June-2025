# Remote Work Health Impact Survey Analysis June 2025
Exploring remote work's mental & physical health impact post-pandemic<br>
**Project OverView**<br>
To analyze how mental health status is impacted by different work arrangements (remote, onsite, and hybrid)<br>
To evaluate how physical health is affected under various work models<br>     
**Tools and Technologies:**<br>
Google Colab notebook<br>
Python - Pandas for read data from CSV and data manipulation<br>
Visualization Library: Bokeh<br>
Dashboard: PowerBI<br>
**Dataset:**<br>
post_pandemic_remote_work_health_impact_2025.csv : https://www.kaggle.com/datasets/pratyushpuri/remote-work-health-impact-survey-2025<br>
The "Post-Pandemic Remote Work Health Impact 2025" - remote, hybrid, and onsite work arrangements are influencing the mental and physical health of employees in the post-pandemic era. <br>
Collected in June 2025, this dataset aggregates responses from different continents, industries, age groups, and job roles.<br>
Columns: Survey_Date, Age, Gender, Region, Industry, Job_Role, Work_Arrangement, Hours_Per_Week, Mental_Health_Status, Work_Life_Balance_Score, Physical_Health_Issues, Salary_Range, etc<br>
3157 Rows<br>
**Data Preparation and Cleaning:**<br>
Replaced missing values to fill with "No issues"<br>
Check if there any duplicated values in row entry<br>
Data Standardization : Converted Survey_Date object to datetime64<br>
**Exploratory Data Analysis(EDA):**<br>
Age Distribution on Survey Respondents<br>
![AgeDistributionOfRespondentsByAge](https://github.com/user-attachments/assets/e9279675-bd7c-4669-9502-ced0c24726c6)

Age Distribution on Survey Respondents with range of values<br>
![AgeDistributionOfRespondentsByRange](https://github.com/user-attachments/assets/add77560-72c3-4add-b607-e1410be1ef04)

Gender Distribution on Survey Respondents<br>
![GenderDistributionOfRespondents](https://github.com/user-attachments/assets/9b460697-22bb-406e-8dfb-da89f0408177)

**Data Analysis and Visualization:**<br>
Mental Health Status by Work Arrangement<br>
Grouped BarChart of Mental Health Status by Work Arrangement<br>
![MentalHealthStatusByWorkArrangement](https://github.com/user-attachments/assets/374ee14d-4ad7-4a9e-b4e0-54512eb29a37)

Physical Health Issues by Work Arrangement<br>
Heatmap of Physical Health Issues by Work Arrangement<br>
![PhysicalHealthStatusByWorkArrangement](https://github.com/user-attachments/assets/dd4e6646-4b02-49a1-a910-a8360cb0f0b9)

**Dashboard:**<br>
Distribution of respondents count by Age, Gender, Region and Job role<br>
![image](https://github.com/user-attachments/assets/ce55e256-57b3-4f78-9647-2c42f8ec776d)

Visualization of Work Arrangement impact on Mental health and Physical health<br>
![image](https://github.com/user-attachments/assets/b86e3210-b1a4-4a18-a6e0-fbe5c6e5d153)

Work arrangement impact on Burnout and Social isolation<br>
![image](https://github.com/user-attachments/assets/84aedb72-b7eb-4c75-91a0-ce328bf45caa)
**Key Insights:**<br>
People reported better mental health while working remotely compared to onsite or hybrid work.<br>
Remote work caused fewer physical health problems than onsite or hybrid work.<br>
Onsite work led to more mental and physical stress overall.<br>
Burnout levels were highest among people working onsite.<br>
Social isolation was reported higher in remote work settings, and lower in onsite work environments.




