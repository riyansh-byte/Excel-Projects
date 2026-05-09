# 📊 Excel Projects Portfolio

Data analysis and dashboard projects built in Microsoft Excel.

---

## 🏢 HR Attrition Analytics Dashboard

**Tool:** Microsoft Excel  
**Dataset:** IBM HR Analytics Employee Attrition & Performance (Kaggle)  
**Records:** 1,470 employees × 35 attributes  

---

### 📌 Project Overview
Analyzed employee attrition patterns from IBM's HR dataset to identify
key drivers of employee turnover across departments, age groups,
salary bands and job roles.

---

### 🔧 Process Followed

**Phase 1 — Data Cleaning**
- Removed redundant columns (EmployeeCount, Over18, StandardHours)
- Removed synthetic columns (DailyRate, HourlyRate, MonthlyRate)
- Created Age Group column — Junior / Mid-Career / Senior
- Created Salary Band column — Low / Medium / High
- Created Distance Range column — 0-10 KM / 10 KM+
- Created Attrition Flag (Yes=1 / No=0) for numeric calculations

**Phase 2 — Analysis**
- Built 4 Pivot Tables analyzing attrition by Department, Age Group, Job Role and Salary Band
- Calculated attrition rate for each segment

**Phase 3 — Dashboard**
- Built interactive dashboard with 4 charts
- Added 5 slicers — Gender, OverTime, Distance Range, MaritalStatus, Salary Band
- All slicers connected to all charts simultaneously
- Added KPI cards — Total Employees, Total Attrition, Attrition Rate
- Added Key Insights section with business findings

---

### 📊 Key Findings
- Sales department has highest attrition at **20.63%**
- Junior employees (≤25) at highest risk — **35.7% attrition rate**
- Low salary band accounts for **47.7%** of total attrition
- Sales Executive & Lab Technician account for **50%+ of departures**
- Company attrition rate of **16.12%** exceeds healthy industry benchmark of 10%

---

###
