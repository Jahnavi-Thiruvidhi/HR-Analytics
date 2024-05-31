## HR Analytics Dashboard Using PowerBI
## Dataset Overview
Our comprehensive dataset includes employee information such as age, gender, attrition, business travel, department, field of education, monthly salary, job role, years at the company, and more.
## Dashboard
<!DOCTYPE html>
<html lang="en">
<body>
    <img src="https://github.com/Jahnavi-Thiruvidhi/HR-Analytics/blob/main/DashBoard%20.png?raw=true" >

</body>
</html>

## 🔍 Analysis Objective<br>
Our aim is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention.

Throughout this project, I've had the chance to:

~ Dive deep into HR data to uncover valuable insights.<br>
~ Develop interactive dashboards to visualize key HR metrics.<br>
~ Provide data-driven recommendations for strategic decision-making.<br>

## 🛠️ Tool Used<br>
Powered by Microsoft Power BI, this report offers intuitive visualizations and interactive features.

## Steps followed:
1. Data Gathering:

   ~ Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.

2. Data cleaning:

   ~ Cleaning is done by removing empty column, removing duplicates, errors etc.<br>
   ~ Replacing values in column with proper values and naming.<br>
   ~ Detecting data type of every column, using the auto detect data type function in Power query editor.<br>

3. Data processing:

   ~ In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF 
     attrition = 'Yes' then 1, Else 0).<br>
   ~ This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = 
     SUM([AttritionCount]))/SUM([Employeecount])) in %.<br> 

4. Data analysis:

   ~ Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant 
     visualizations.<br>
   ~ These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.<br>
   
## Key Insights💡<br>
1️⃣ We observed an overall attrition rate of 16.12% among our workforce of 1470 employees.<br>
2️⃣ 17% of the Male workforce, i.e. 150 males and 15% of the Female workforce, i.e. 87 females left the organization.<br>
3️⃣ The attrition rate of High School is 18.24% which is maximum among the other education.<br>
4️⃣ The age group of 25-34 years had the highest attrition rate, warranting targeted retention strategies for this demographic.<br>
5️⃣ There are more number of employees under the age group of 25-34 years.<br>
6️⃣ The attrition rate of R&D Department is maximum with 90%<br>


