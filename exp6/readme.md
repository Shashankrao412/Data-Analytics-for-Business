# Employee Insights Dashboard – Power BI

## 📊 Project Overview

The **Employee Insights Dashboard** is an interactive Power BI dashboard designed to analyze employee attrition and workforce-related information.

The dashboard provides insights into employee attrition based on different factors such as **department, job role, gender, education field, business travel, marital status, job level, job satisfaction, and years at company**.

The main objective of this project is to help HR teams understand employee turnover patterns and identify factors that may contribute to employee attrition.

---

## 🎯 Objectives

* Analyze overall employee attrition.
* Calculate and monitor the employee attrition rate.
* Understand attrition across different departments.
* Analyze attrition by job role and job level.
* Compare attrition based on gender and marital status.
* Analyze the relationship between education field and attrition.
* Study the impact of business travel on employee attrition.
* Analyze attrition based on job satisfaction.
* Understand attrition trends based on years spent at the company.
* Provide interactive filters for detailed HR analysis.

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Visualization**
* **Data Cleaning & Transformation**
* **Microsoft Excel / CSV Dataset**

---

## 📁 Dashboard Structure

The report contains two dashboard pages.

### Page 1 – Employee Insights Dashboard

The first page provides an overall summary of employee attrition.

### KPI Cards

The dashboard contains the following key performance indicators:

* **Total Employees**
* **Attrition Count**
* **Attrition Rate**
* **Average Age**
* **Average Monthly Income**
* **Average Years at Company**

### Visualizations

The dashboard includes:

* Attrition by Department
* Attrition by Job Role
* Attrition by Gender
* Attrition by Business Travel
* Attrition by Education Field
* Attrition by Years at Company

### Interactive Slicers

Users can filter the dashboard using:

* Department
* Job Role
* Education Field
* Business Travel
* OverTime

---

## 📈 Page 2 – Detailed Employee Analysis

The second page provides more detailed analysis of employee attrition.

### Visualizations

* Attrition by Marital Status
* Attrition Rate vs Target
* Attrition by Job Level
* Attrition by Department
* Attrition by Job Satisfaction
* Employee-level detail table
* Employee Income vs Total Working Years scatter plot

### Employee Detail Table

The detailed table provides information such as:

* Department
* Attrition
* Job Role
* Age
* Gender
* Monthly Rate
* Years at Company

---

## 📌 Key Metrics

The dashboard uses important HR metrics such as:

### Attrition Count

Represents the number of employees who have left the organization.

### Attrition Rate

Measures the percentage of employees who have left compared with the total employee population.

**Formula:**

```text
Attrition Rate =
Number of Employees Who Left / Total Employees × 100
```

### Average Age

Represents the average age of employees in the organization.

### Average Monthly Income

Represents the average monthly income of employees.

### Average Years at Company

Represents the average number of years employees have worked for the organization.

---

## 📊 Business Insights

The dashboard can help HR management:

* Identify departments with higher employee attrition.
* Determine job roles experiencing greater employee turnover.
* Understand demographic patterns associated with attrition.
* Analyze whether frequent business travel is associated with employee turnover.
* Examine the relationship between job satisfaction and attrition.
* Identify attrition patterns across different job levels.
* Understand how employee tenure affects attrition.
* Support data-driven employee retention strategies.

---

## 🔄 Data Preparation

The dataset was prepared using Power BI and Power Query.

The general data preparation process includes:

1. Importing the employee dataset.
2. Checking data types.
3. Handling missing or inconsistent values.
4. Removing unnecessary columns where required.
5. Validating categorical values.
6. Creating calculated measures using DAX.
7. Building relationships and data models where required.
8. Creating visualizations and interactive filters.

---

## 🧮 DAX Measures

Important measures used in the dashboard include:

```DAX
Total Employees = COUNTROWS(Exp_6)
```

```DAX
Attrition Count =
CALCULATE(
    COUNTROWS(Exp_6),
    Exp_6[Attrition] = "Yes"
)
```

```DAX
Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees],
    0
)
```

Additional measures are used for:

* Average Age
* Average Monthly Income
* Average Years at Company

---

## 🎨 Dashboard Design

The dashboard uses a clean **blue and white professional HR theme**.

Design features include:

* KPI cards
* Rounded visual containers
* Interactive slicers
* Bar charts
* Column charts
* Line charts
* Pie and donut charts
* Treemap
* Gauge chart
* Scatter plot
* Detailed tables

The visuals are designed to make HR information easy to understand and compare.

---

## 🚀 How to Use

1. Download or clone this project.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Navigate between the dashboard pages.
4. Use the slicers to filter employee information.
5. Select different visual elements to cross-filter other charts.
6. Analyze the displayed HR metrics and employee attrition patterns.

---

## 📂 Project File

```text
assignment_hr_6.pbix
```

---

## 💡 Conclusion

The **Employee Insights Dashboard** provides an interactive and data-driven approach to understanding employee attrition.

By combining HR KPIs, charts, filters, and detailed employee information, the dashboard enables HR managers and decision-makers to identify attrition patterns and make better workforce-management decisions.

Overall, this project demonstrates the use of **Power BI, Power Query, DAX, data visualization, and business intelligence techniques** for HR analytics.

---

## 👨‍💻 Author

**Shashank Rao R**

MCA Student | Data Analytics & Machine Learning Enthusiast

**Skills:**
Python | SQL | Power BI | DAX | Machine Learning | Data Analytics | Data Visualization
