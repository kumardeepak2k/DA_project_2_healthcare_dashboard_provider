# Healthcare Provider Dashboard – Power BI Project  

## 🏥 **Project Overview**  
This project is a comprehensive **Healthcare Provider Dashboard** built using **Power BI** to analyze over **£2M+** in healthcare financial and operational data. The goal was to provide clear insights into billing, treatment costs, and departmental performance, helping healthcare providers make better strategic decisions.  

---

## 🚀 **Key Features**  
- **Data Model:** Built a star schema model with **10+ tables** (patients, procedures, diagnoses, insurance, departments, etc.).  
- **Custom Date Table:** Created using DAX for time-based analysis (monthly, quarterly, yearly).  
- **KPIs and Insights:** Developed **6 KPIs** to track key metrics like billing amount, medication cost, and treatment cost.  
- **Interactive Filters:** Added **6 filters** (race, year, quarter, city, department, procedure) for better insights.  
- **Performance Optimization:** Reduced query load time by **30%** using Power Query and efficient DAX.  
- **High-Cost Areas:** Identified high-cost areas like **cardiology (£165K)** and **imaging procedures (£178K)**.  

---

## 📊 **Data Model Overview**  
The data model follows a **star schema** design, ensuring efficient data relationships and quick aggregations:  
- **Fact Table:** Visits (admissions, discharges, billing, insurance).  
- **Dimension Tables:** Patients, Procedures, Diagnoses, Departments, Insurance, Date Table.  

---

## 🌟 **Challenges and Solutions**  
- **Data Availability:** Finding good healthcare data was difficult; I used publicly available UK data.  
- **Data Cleaning:** Cleaned and transformed inconsistent data using Power Query.  
- **Performance:** Reduced lag and improved responsiveness with indexed columns and optimized DAX.  

---

## 🏆 **Key Insights**  
✅ Cardiology, General Surgery, and Orthopedics drive most of the revenue.  
✅ Imaging procedures (X-Ray and CT Scan) generate the highest billing amounts.  
✅ Hypertension and appendicitis cases are primarily outpatient visits.  
✅ Regional variation shows potential for growth in smaller cities.  

---

## 🛠️ **Tools & Technologies**  
- **Power BI**  
- **DAX (Data Analysis Expressions)**  
- **Power Query**  
- **Star Schema Data Modeling**  

---

## 📂 **Project Files**  
- **Healthcare_Dashboard.pbix** – Power BI file  
- **README.md** – Project documentation  

---

## 🔗 **Links**  
- **[Medium Article](https://medium.com/@kumardeepaks2k/building-a-healthcare-provider-dashboard-with-power-bi-34a55091fe36)**

---

## ✍️ **Credits**  
- Special thanks to ** Ismaila Omeiza M.**, creator of "Data with Decision" for the dataset and guidance throughout the project.  

---

## 💡 **Contact**  
If you found this project helpful or have suggestions, feel free to reach out! 😊  
