# 📊 Employee Work Productivity Analysis  

## 📌 Project Summary  
This project focuses on analyzing employee productivity data using **Excel**.  
The dataset contains employee work details such as hours worked, tasks completed, productivity scores, and performance ratings.  
Through various functions, PivotTables, and charts, the analysis highlights **top performers, departmental consistency, efficiency metrics, and correlations** between work factors and performance.  

The end goal is to uncover actionable insights that can help organizations improve employee utilization and boost overall productivity.  

---

## ✅ Analyses Performed

### 1. Top 5 Productive Employees
- Sorted employees by **Productivity_Score**.  
- Used **SORT + FILTER** functions.  
- Created a **bar chart** to visualize the top 5.  

---

### 2. Department-Wise Productivity Consistency
- Calculated the **standard deviation of Productivity_Score** within each department.  
- Identified the department with the **least variation** in performance.  
- Used **PivotTable with STDEV.P** for department grouping.  

---

### 3. Productivity Efficiency Index (PEI)
- Created a new column using:  
  ```text
  PEI = (Productivity_Score × Performance_Rating) / Hours_Worked
  ```  
- Ranked all employees by PEI.  
- Highlighted the **Top 3 employees** with highest efficiency.  

---

### 4. Correlation Analysis
- **1:** Compared correlation of `Hours_Worked` vs `Performance_Rating` and  
  `Tasks_Completed` vs `Performance_Rating`.  
- Used **CORREL function** → Found which factor had stronger impact.  
- **2:** Created a **scatter plot** of `Hours_Worked` vs `Productivity_Score` to check if the relationship was positive or negative.  

---

### 5. Underutilized High Performers
- Identified employees with:  
  - `Performance_Rating ≥ 4`  
  - `Hours_Worked < Average(Hours_Worked)`  
- Used **AVERAGE + FILTER + logical conditions**.  
- These employees were flagged as **efficient but underutilized**.  

---

### 6. Tasks per Hour Efficiency
- Added a new column:  
  ```text
  Tasks_per_Hour = Tasks_Completed / Hours_Worked
  ```  
- Found the **most task-efficient employee**.  
- Compared their `Productivity_Score` and `Performance_Rating` with others.  
- Used **MAX + INDEX-MATCH/XLOOKUP**.  

---

## 📈 Deliverables
- **Tables:** Top performers, PEI rankings, Task Efficiency.  
- **Charts:**  
  - Bar chart → Top 5 Employees  
  - Scatter plot → Hours vs Productivity  
- **Insights:**  
  - Department with most consistent productivity  
  - Stronger factor influencing performance  
  - Underutilized high performers  

---

## 🛠️ Tools Used
- **Excel**  
- Functions:  
  - `SORT`, `FILTER`, `RANK`, `STDEV.P`, `CORREL`, `INDEX-MATCH`, `XLOOKUP`, `AVERAGE`  
- PivotTables & Charts  

---
