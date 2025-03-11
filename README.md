# CTA Ridership Data Analysis Project  

This Tableau project analyzes **Chicago Transit Authority (CTA) ridership trends (2015-2024)** using data from [Data.gov](https://data.gov/)  
CTA Dataset: [CTA Ridership Daily Boarding Totals](https://catalog.data.gov/dataset/cta-ridership-daily-boarding-totals)  

The project includes multiple visualizations to explore trends over time (2015-2024), including **two dashboards and two heatmaps**. The design follows **CTA’s official color scheme** to ensure visual consistency.  

---

## 📂 About the Dataset  

This dataset contains daily boarding totals for CTA services, covering both bus and rail rides. The data has been **filtered to include records from January 1, 2015, to December 31, 2024**.  

### **Dataset Columns & Explanation**  
- **Service Date (Date Field)** – Represents the date for which the ridership data is recorded.  
- **Day Type (String Field)** – Classifies the day into three categories:  
  - **W** – Weekday  
  - **A** – Saturday  
  - **U** – Sunday/Holiday  
- **Bus Boardings (Numerical Field)** – Total number of bus rides on a given day.  
- **Rail Boardings (Numerical Field)** – Total number of rail rides on a given day.  
- **Total Rides (Numerical Field)** – The sum of bus and rail boardings for that day.  

---

## 📊 Dashboards  

### **Dashboard 1: Overview of CTA Ridership Trends**  
This dashboard provides a **high-level summary of CTA ridership**, offering insights into overall trends:  
- **Total Rides by Day Type (Pie Chart)** – Displays the proportion of rides taken on weekdays, Saturdays, and Sundays/Holidays.  
- **Total Rides by Month (Pie Chart)** – Shows ridership distribution across different months.  
- **Total Rides by Month (Line Chart)** – Tracks monthly ridership trends from 2015 to 2024.  
- **Filters** – Allows users to filter data by **year, quarter, month, and day type** for a customized view.  

### **Dashboard 2: Comparative Analysis of CTA Ridership**  
This dashboard enables **detailed comparisons and trend analysis** of CTA ridership:  
- **Bus vs. Rail Boardings by Day Type (Side-by-Side Bar Chart)** – Compares daily bus and rail ridership across different day types.  
- **Quarterly Rides by Year (Stacked Bar Chart)** – Displays ridership trends across all four quarters for each year.  
- **Yearly Trends for Bus and Rail (Dual-Axis Line Chart)** – Highlights annual ridership trends for both transportation modes.  
- **Quarterly Trends in Total Rides Over Time (Line Chart)** – Shows quarterly fluctuations in overall ridership.  
- **Filters** – Allows selection by **year, quarter, month, and day type** to explore specific trends.  
- **Average Line** – Provides an **average ridership benchmark** to help analyze whether a particular quarter’s ridership was above or below the historical average.

### **Dynamic Feature:** 
- **Reset Filters Button** – Enables users to **clear all applied filters** and restore the default view. It restores default settings by clearing all selected filters.  
- **All filters impact every visualization simultaneously**, ensuring an **interactive and seamless experience** when analyzing trends.  

---

## 🔥 Heatmaps  

### **1. Rides by Month (Heatmap)**  
- This heatmap visually represents **monthly ridership trends**, identifying months with higher or lower ridership.  
- **Darker shades indicate higher ridership**, while lighter shades represent lower ridership.  

### **2. Rides by Day Type and Month (Heatmap)**  
- Expands on the first heatmap by breaking down ridership by **day type (Weekday, Saturday, Sunday/Holiday)**.  
- Highlights which months experience peak or low ridership on specific days of the week.  

---

## 📈 **Key Learnings & Insights**  

### **Impact of COVID-19 on CTA Ridership**  
- A **sharp decline in ridership is evident during 2020-2021**, aligning with the pandemic’s impact.  
- **Bus and rail boardings dropped significantly**, especially during lockdown periods.  
- **Monthly and quarterly trends confirm that ridership post-COVID remains lower than pre-pandemic levels**, though a gradual recovery is visible.

### **Design & Color Matching**  
- The dashboards follow **CTA’s official color scheme** for brand alignment.  
- Heatmaps use **color intensity** to emphasize ridership variations effectively.  

---

## 🚀 How to View the Project  
1. **Download** the Tableau project files from this repository.  
2. **Open** the `.twbx` file in Tableau Desktop.  
3. **Interact** with the dashboards, apply filters, and analyze ridership trends.  
