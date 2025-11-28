# HR-Analytics-Dashboard
Power BI HR Analytics report analyzing attrition trends by gender, age, job role,  salary and years at company.
This report provides a detailed analysis of employee attrition across departments, job roles, demographics, and compensation levels. It is designed to help HR leaders and business managers understand workforce trends, identify risk factors, and develop strategies to improve retention.

**Key Highlights**:	

	
Overall Workforce Metrics

• 	Total employees: 1,423

• 	Attrition count: 211

• 	Attrition rate: 14.8%

• 	Average age: 38 years

• 	Average tenure: 7.23 years

• 	Average salary: 6.67K
![dashboard](https://github.com/user-attachments/assets/4e1b956e-aef6-4480-8a9c-d7593feefd9b)

**Data Cleaning Process 🧹**

Before analysis, the dataset was cleaned to ensure accuracy and consistency:

- **Duplicates Removed:** Employee records with repeated IDs were eliminated.
    
- **Missing Values:** Nulls in salary and age were handled (either imputed or excluded).

- **Date Formatting:** Standardized tenure values to ensure correct calculations.  

![Screenshot 2025-11-28 235017](https://github.com/user-attachments/assets/d1f202e2-52b9-4d09-bbf3-04079049403c)


**Attrition by Demographics**

• 	Gender: 138 males vs 73 females

**Insight →** Attrition is higher among men, possibly due to role distribution in sales and technical jobs.

• 	Age groups: Highest attrition in 26–35 years (43) and 18–25 years (116)

**Insight →** Early-career employees (18–25) are most vulnerable, showing retention challenges in onboarding and career growth.

**Attrition by Job Role**

Top roles affected: Sales Executive (58), Laboratory Technician (53), Research Scientist (41)

Other roles include Sales Representatives, HR, Healthcare Representatives, and Managers.

**Insight →** Sales and lab roles show the highest attrition, suggesting stress, workload, or limited career progression.

![Screenshot 2025-11-28 231717](https://github.com/user-attachments/assets/da918a74-9f20-4e20-a3c9-067addfbe690)
![Screenshot 2025-11-28 232013](https://github.com/user-attachments/assets/4c379ab5-9158-4175-9073-73216ce79ddb)



**Attrition by Education**

• 	Life Sciences: 38%

• 	Medical: 27%

• 	Marketing: 15%

• 	Technical Degree: 13%

• 	Other: 4

![Screenshot 2025-11-28 235243](https://github.com/user-attachments/assets/4a7e61d4-f0e3-4161-be86-4129ad88705b)


**Insight →** Attrition is concentrated among Life Sciences and Medical graduates, possibly reflecting industry-specific challenges.

**Attrition by Salary Slab**

• Majority from lower salary bands: 136 employees earning up to 5K

• Attrition decreases significantly in higher salary ranges.

• Attrition by Tenure

• Highest attrition among employees with 1–3 years at the company.

• Very low attrition among long-tenured employees.

![Screenshot 2025-11-28 235343](https://github.com/user-attachments/assets/1185e95f-10d4-481d-93b9-afdd4607ba01)


**Insight →**Majority of attrition occurs in the lowest salary slab, showing compensation as a key retention lever.

**Key Insights 🔑**

• 	Younger, lower-paid employees in sales and lab roles are most at risk.

• 	Salary and career development opportunities appear central to retention.

• 	Compensation and career growth initiatives could reduce attrition.

• 	Mid-career employees show stability, suggesting that retention improves once employees are established.

**Conclusion 🏁**

This analysis highlights the importance of targeted retention strategies for early-career employees, especially in sales and technical roles.
Improving compensation, career growth, and engagement could significantly reduce attrition and strengthen workforce stability.

**How to Use 🚀**

1. 	Clone this repository.
   
2. 	Open the Power BI file ().
   
3. 	Explore the interactive dashboard with filters for gender, department, and education.

Project Structure 📂

HR-Analytics/

│

├── data/  							# Raw and cleaned datasets

├── dashboard/ 		          		# Power BI .pbix file

├── images/	              			# Screenshots of dashboard visuals

├── scripts/             			# DAX formulas or Power Query steps

└── README.md           			# Project documentation



13. Screenshots 📸
- Dashboard Overview
- Attrition by Age
- Attrition by Job Role
- Attrition by Salary
- Power Query (Data Cleaning)
  

14. License 📜
This project is open-source. Feel free to use and adapt it for learning or organizational insights.



