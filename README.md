# 🏥 Hospital Appointment Analysis – CarePlus Hospitals

## 📌 Project Overview
This project analyzes hospital appointment data to understand patient trends, department performance, revenue patterns, and cancellation impact.  
The goal is to provide data-driven insights to improve hospital efficiency, reduce waiting time, and increase revenue.

---

## 🎯 Business Objectives
- Reduce patient waiting time by **20%**
- Increase weekday appointment bookings by **15%**
- Identify underperforming departments
- Analyze cancellation impact on revenue
- Provide actionable recommendations for hospital management

---

## 📊 Dataset Description
The dataset contains **500 hospital appointment records** across Bangalore, Mysore, and Chennai.

### Key Columns
- AppointmentID
- Date
- City
- Doctor
- Department
- AppointmentFee
- WaitingTime
- Cancelled
- PatientType
- Cost

Missing values were intentionally included in **PatientType** and **Cost** fields to simulate real-world data challenges.

---

## 🛠 Tools Used
- **SQL Server Management Studio (SSMS)** – Data cleaning & analysis
- **Power BI** – Dashboard & visualization
- **Excel** – Dataset creation & preprocessing
- **GitHub** – Project documentation

---

## 🧹 Data Cleaning Steps
- Replaced missing `PatientType` values with **"New"**
- Replaced missing `Cost` values with average cost
- Calculated **Profit = AppointmentFee – Cost**
- Converted Date column to proper date format

---

## 📈 Exploratory Data Analysis (EDA)

### 1️⃣ Department Performance
- Some departments generated higher revenue than others.
- Departments with higher waiting time showed higher patient demand.

### 2️⃣ Weekend vs Weekday Analysis
- Weekday appointments were higher than weekend bookings.
- Indicates missed revenue opportunities on weekends.

### 3️⃣ Cancellation Analysis
- Higher waiting time led to higher cancellation rate.
- Cancellations reduce revenue and waste doctor availability.

### 4️⃣ City-wise Performance
- Revenue varied across Bangalore, Mysore, and Chennai.
- Certain cities contributed higher revenue due to higher patient demand.

### 5️⃣ Doctor Performance
- Some doctors generated higher revenue due to higher appointment volume.

---

## 📊 Power BI Dashboard Features
- KPI Cards:
  - Total Appointments
  - Total Revenue
  - Total Profit
  - Cancel Rate
  - Avg Waiting Time
- Revenue by City Chart
- Waiting Time by Department Chart
- Monthly Appointment Trend
- Patient Type Distribution
- Doctor Performance Table
- Interactive Filters (City, Department, Doctor)

---

## 🔑 Key Insights
- High-demand departments need more staffing.
- Weekday appointments outperform weekend bookings.
- High waiting time increases cancellations.
- Revenue varies significantly across cities and doctors.
- Repeat patients generate consistent revenue.

---

## 💡 Business Recommendations

### ✅ Quick Wins
- Add staff to high-wait departments
- Send SMS reminders to reduce cancellations
- Introduce weekend appointment offers
- Optimize doctor scheduling

### 🚀 Long-Term Strategies
- Implement online appointment optimization
- Introduce loyalty program for repeat patients
- Demand-based staffing using analytics
- Improve hospital resource planning

---

## ⚠ Assumptions & Limitations
- Dataset represents simulated hospital data
- Missing PatientType treated as "New"
- Missing Cost replaced with average
- Seasonal disease trends not analyzed

---

## 📌 Conclusion
This project demonstrates how SQL and Power BI can be used to analyze hospital operations, identify inefficiencies, and provide actionable insights to improve patient satisfaction and hospital revenue.

---

## 🎤 Interview Explanation (Short Version)
> I analyzed hospital appointment data using SQL Server and Power BI.  
> I cleaned missing data, calculated KPIs like revenue per city and cancel rate, and built interactive dashboards to identify departments with long waiting times and recommend operational improvements.

---

## 📂 Files Included
- hospital_appointments.csv
- SQL_queries.sql
- PowerBI_dashboard.pbix
- Final_Report.pdf
- README.md

---

## ⭐ Author
**Ankitha D**
