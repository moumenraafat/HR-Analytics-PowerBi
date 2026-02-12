
# 📊 HR Analytics Dashboard (Power Bi)

## 📌 Overview
In this project, I used **Power BI** to create an interactive **HR Analytics Dashboard** that helps organizations decision makers track and analyze their workforce. 
The dashboard provides insights into employee demographics, performance, attrition, and satisfaction levels, enabling data-driven HR decisions.

---

## 📊 Dataset
The dataset contains employee information including:
* **Demographics:** Age, gender, marital status, ethnicity.
* **Employment details:** Department, job role, tenure, business travel, overtime.
* **Performance metrics:** Satisfaction levels, ratings, work-life balance.
* **Attrition:** Active vs. inactive employees, attrition rate.

---

## 📈 Dashboard Features

### 1. Overview Page
* Total Employees, Active Employees, Inactive Employees.
* Attrition Rate (%).
* Employee Hiring Trends.
* Active Employees by Department & Job Role.

### 2. Demographics Page
* Employee distribution by **Age & Gender**.
* Employees by **Marital Status**.
* Employees by **Ethnicity and Average Salary**.
* Youngest & Oldest Employee indicators.

### 3. Performance Tracker Page
* Job Satisfaction, Environment Satisfaction, Relationship Satisfaction.
* Manager Ratings & Self Ratings.
* Work-Life Balance.
* Drill-through for individual employee performance tracking.

### 4. Attrition Page
* Attrition Rate by **Department & Job Role**.
* Attrition by **Business Travel Frequency**.
* Attrition by **Overtime Requirement**.
* Attrition by **Tenure and Hire Date**.

---

## 🔗 Data Modeling
The project utilizes a **Star Schema** with fact and dimension tables to ensure efficient queries and scalable reporting:

* `FactPerformanceRating`: Performance, satisfaction, ratings.
* `DimEmployee`: Employee info (age, department, travel...etc.).
* `DimDate`: Hire date, attrition date, etc.
* `DimRatingLevel`: Rating categories.
* `DimSatisfactionLevel`: Satisfaction categories.
* `DimEducationLevel`: Education categories.



---

## 💡 Insights
* **Department Focus:** Majority of employees are in Technology & Sales departments.
* **Attrition Drivers:** Higher attrition rates occur in employees with frequent travel and overtime requirements.
* **Retention:** Job satisfaction and work-life balance strongly impact attrition.
* **Demographics:** The 20-29 age group dominates the workforce.

---

## 📷 Dashboard Preview
<img width="1022" height="584" alt="HR-Screenshot 2026-02-10 at 10 17 29 PM" src="https://github.com/user-attachments/assets/cf68ab14-19df-4d75-b285-d5da6c0cdc11" />

<img width="1021" height="573" alt="HR-Screenshot 2026-02-10 at 10 18 59 PM" src="https://github.com/user-attachments/assets/bb46efe6-f9ae-42de-9069-13bf4e17b61f" />

<img width="1017" height="550" alt="HR-Screenshot 2026-02-10 at 10 19 22 PM" src="https://github.com/user-attachments/assets/3c3f63f5-13d8-4164-a55a-a510da3e8e56" />



<img width="1018" height="575" alt="HR-Screenshot 2026-02-10 at 10 19 42 PM" src="https://github.com/user-attachments/assets/3ba4a0de-a943-404e-957c-acdcd58c75b9" />
<img width="1046" height="557" alt="HR-Screenshot 2026-02-12 at 2 50 57 AM" src="https://github.com/user-attachments/assets/b3687a34-cc33-4c40-87ad-e11f9d0b7bde" />
<img width="1303" height="745" alt="HR-Screenshot 2026-02-12 at 2 54 26 AM" src="https://github.com/user-attachments/assets/065e1811-a0d3-42c3-91fb-c89df3e892f3" />
<img width="1261" height="748" alt="HR-Screenshot 2026-02-12 at 2 54 07 AM" src="https://github.com/user-attachments/assets/051b6cf7-d09a-41b1-a2e5-721e18f5b51e" />
<img width="1329" height="772" alt="HR-Screenshot 2026-02-12 at 2 52 52 AM" src="https://github.com/user-attachments/assets/f7742ea4-a916-4ddd-a122-8e0ec323914a" />



---

## 🚀 Tools Used
* **Power BI** – Dashboard creation
* **Power Query** – Data preparation & cleaning
* **DAX** – Complex KPIs and advanced DAX measures
* **ERD (Entity Relationship Diagram)** - To create Data Model Schema

  ---

## 👤 Author
**Moamen Mohamed Raafat** [LinkedIn Profile](https://www.linkedin.com/in/moamen-mohamed-raafat/) | [Portfolio Website](https://moumenraafat.github.io/MoamenMohamedRaafat.github.io/)
