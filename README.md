![Screenshot 2025-05-30 210321](https://github.com/user-attachments/assets/08019c7e-fca5-479e-926a-73c3053ccd01)


# Tableau_PROJECT – HR ANALYTICS DASHBOARD

## Project-1: **HR Insights – Hiring vs Termination Analysis**

### 📌 Introduction

This HR analytics dashboard was built to provide a comprehensive overview of employee lifecycle patterns — from hiring to termination — across departments, locations, and demographics. The dashboard offers key insights into employee distribution, performance, education levels, salary comparisons, and more.

The project helps HR teams and decision-makers understand what’s working and where interventions may be needed, ultimately improving workforce planning.

---

### 🛠 Tableau Features Used

The following Tableau features and skills were utilized for analysis:

- 📊 Visualizations (Bar, Scatter, Pie, Heatmaps)
- 🧮 Calculated Fields
- ⏳ Date-Time Functions
- 🔃 Filters and Interactions
- 📊 Parameters
- 📋 Summary Table
- 🧠 Dashboard Interactivity

---

### 🗃️ Dataset Used

The dataset was sourced from **Kaggle**, representing real-world company HR data with the following attributes:

- 👤 Employee ID, Name, Gender, State, City  
- 🎓 Education Level  
- 🎂 Age  
- 📅 Hire Date, Termination Date  
- 🏢 Department & Job Title  
- 💰 Salary  
- ⭐ Performance Rating

- **Rows:** 8,950  
- **Columns:** 15

---

## 📊 Dashboard Build

### 🔧 Data Preparation & Cleaning

- Cleaned text data (trimmed spaces, unified cases)
- Converted `Hire Date` & `Termination Date` into usable formats
- Created calculated fields for:
  - Age groups (e.g. 25-34, 35-44)
  - Income groups (e.g. 60K–80K, 80K+)
  - Status (Hired, Terminated, Active)
  - Performance Bins
- Handled missing or inconsistent data

---

### 📈 Visuals Created

#### 👥 Demographics Breakdown

- Gender-wise Distribution (Donut Chart)
- Education & Age Heatmap
- Performance vs Education Matrix

#### 📍 Location Analysis

- Map Visualization of employee locations
- HQ vs Branch split bar chart

#### 🧮 Hiring & Termination Trends

- Line chart comparing hiring vs termination over time
- Department-wise Hiring vs Termination bar chart

#### 💰 Income Analysis

- Education & Gender vs Salary (Bar & Bubble)
- Age vs Salary Scatterplot, highlighting job roles
  ![Screenshot 2025-05-30 210423](https://github.com/user-attachments/assets/675056cc-b0bd-45df-babe-c65590e8ad68)
  
#### 📋 Summary Table

- Department-wise breakdown with interactive filters
- Filtered by gender, location, hire date, and employee status

---

## 💡 Insights Gained

- 🚪 Most **terminations happened in 2024**, indicating possible restructuring or high turnover.
- 🏭 The **Operations department** had the highest number of hires and also the most terminations.
- 📍 Nearly **70% of employees work at the headquarters**, showing geographic concentration.
- 👨‍💼 **Males are paid more than females** across most education levels and roles.
- 🎓 Employees with only **high school education had the lowest performance ratings**.

---

## 🧾 Conclusion

This Tableau dashboard provides an interactive view into the hiring, performance, and salary dynamics of a company’s workforce. By combining demographic data with lifecycle metrics, this project uncovers key operational insights:

- **Strategic HR planning** is needed in departments with high churn
- **Upskilling** employees with low education levels may boost performance
- **Addressing gender pay gaps** is crucial for equality and retention

---


