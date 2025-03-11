# CTA Ridership Data Analysis Project  

This Tableau project analyzes **Chicago Transit Authority (CTA) ridership trends (2015-2024)** using data from [Data.gov](https://data.gov/)  
CTA Dataset: [CTA Ridership Daily Boarding Totals](https://catalog.data.gov/dataset/cta-ridership-daily-boarding-totals)  

The project includes multiple visualizations to explore trends over time (2015-2024), including **two dashboards and two heatmaps**. The design incorporates **CTA’s official logo colors** to enhance visual consistency.  

---

## 📂 About the Dataset  

This dataset contains daily boarding totals for CTA services, including rail and bus rides. The data has been **filtered to include records from January 1, 2015, to December 31, 2024**.  

### **Dataset Columns & Explanation**  
- **Service Date** – The date for which the ridership data is recorded.  
- **Day Type** – Categorizes the day as a **Weekday (W), Saturday (A), or Sunday/Holiday (U)**.  
- **Bus Boardings** – Total number of bus rides on a given day.  
- **Rail Boardings** – Total number of rail rides on a given day.  
- **Total Rides** – Sum of bus and rail boardings for the day.  

---

## 📊 Dashboards  

### **Dashboard 1: Overview of CTA Ridership Trends**  
This dashboard provides a high-level summary of CTA ridership, including:  
- **Total Rides by Day Type (Pie Chart)** – Shows the total rides taken on weekdays, Saturdays, and Sundays/Holidays.  
- **Total Rides by Month (Pie Chart)** – Displays ridership distribution across all months.  
- **Total Rides by Month (Line Chart)** – Trends in monthly ridership from 2015 to 2024.  
- **Filters** – Users can filter data by **year, quarter, month, and day type** for a customized view.  
- **Reset Filters Button** – Allows users to **clear all applied filters** and return to the default view.  

### **Dashboard 2: Comparative Analysis of CTA Ridership**  
This dashboard explores comparisons and trends in ridership:  
- **Bus vs. Rail Boardings by Day Type (Bar Chart)** – Compares bus and rail ridership across weekdays, Saturdays, and Sundays/holidays.  
- **Quarterly Rides by Year (Stacked Bar Chart)** – Displays ridership trends across all four quarters for each year.  
- **Yearly Trends for Bus and Rail (Dual-Axis Line Chart)** – Shows annual trends in ridership for both transportation modes.  
- **Quarterly Trends in Total Rides Over Time (Line Chart)** – Highlights fluctuations in total ridership across quarters.  
- **Filters** – Allows selection by **year, quarter, month, and day type** to analyze specific patterns.
- **Average Line** – An **average ridership metric** has been added to analyze performance trends, identifying periods where ridership was below or above the historical average.  

💡 **Dynamic Feature:**  
All filters **affect every visualization simultaneously**, ensuring an **interactive and cohesive experience** when exploring trends.  

---

## 🔥 Heatmaps  

### **1. Rides by Month (Heatmap)**  
- This heatmap visually represents **monthly ridership trends**, highlighting months with higher or lower ridership.  
- **Darker colors indicate higher ridership**, while lighter colors represent lower ridership.  

### **2. Rides by Day Type and Month (Heatmap)**  
- Similar to the first heatmap, but this one breaks down ridership by **day type (Weekday, Saturday, Sunday/Holiday)**.  
- Helps identify which months have the highest or lowest ridership on specific days of the week.  

---

## 📈 **Key Learnings & Insights**  

### 📉 **Impact of COVID-19 on CTA Ridership**  
- The **2020-2021 period shows a significant drop** in ridership due to the pandemic, with all charts reflecting a steep decline.  
- **Bus and rail boardings fell sharply**, especially during lockdown months.  
- **Monthly and quarterly trends reveal that ridership post-COVID remains below pre-pandemic levels**, but is gradually increasing.  

### 📊 **Post-Pandemic Trends**  
- **Quarterly performance remains below the historical average**, though there is **a slow upward trend** in ridership recovery.  
- Weekday ridership has rebounded **faster than weekend ridership**, possibly due to commuters returning to work.  

### 🎨 **Color Matching with CTA Logo**  
- The dashboard design follows **CTA’s official color scheme** to maintain brand alignment.  
- Heatmaps use **gradient intensity** to represent variations in ridership levels effectively.  

---

## 🚀 How to View the Project  
1. **Download** the Tableau project files from this repository.  
2. **Open** the `.twbx` file in Tableau Desktop.  
3. **Interact** with the dashboards, apply filters, and analyze trends.  

---

This README provides a **comprehensive overview** of the project, dataset, key insights, and interactive features. Let me know if you'd like any refinements! 🚀
```  
