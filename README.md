# Power-BI
<br>

# 📊 Dynamic Latest Month Filtering in Power BI

**📁 Project Overview**

This Power BI report demonstrates how to **dynamically lock visuals to the latest available month of data**, based entirely on the data loaded into the model — not based on today's date.

This approach is helpful when:
- Data is updated irregularly or in batches
- You want your visuals to **always reflect the most recent period** in the dataset
- The "latest month" should reflect what's in the data — not the system calendar

**✅ Benefits**

- No need to update filters manually  
- Works regardless of when data is refreshed or uploaded  
- Keeps reports consistent and focused on the most recent insights

**💡 Use Case Example**

If your dataset contains records only up to **April 2028**, the report will auto-filter to April 2028.  
If the next time you refresh the dataset and the latest data ends at **October 2029**, the visuals will automatically shift to show October 2029 — **without editing anything**.

---
<br>

# 📈 Cumulative Monthly Filtering in Power BI

**📁 Project Overview**

This Power BI report showcases a method to **dynamically display data from the beginning of a selected year up to a user-selected month**. It meets a common business requirement: instead of filtering to just a single month, users want to see the **cumulative values from January to the selected month**.

**✅ Benefits**

- Gives users intuitive control over how much of the year’s data they want to see  
- Enables powerful **year-to-date** or **partial period comparisons**  
- Makes the report more **user-friendly and dynamic**

**💡 Use Case Example**

If the user selects **Year = 2020** and **Month = August**, the report will display data from **January to August 2020**, rather than just August.

---
<br>

# 📊 Linear Gauge with Normalized Grading in Power BI

**📁 Project Overview**

In this project, I built a **linear gauge-style bar chart** in Power BI to visualize performance metrics by grading them from **Grade 1 (lowest)** to **Grade 5 (highest)**. This was based on real user requirements where each metric had **non-uniform and varying value ranges**, making traditional charting methods ineffective.

**✅ Benefits**

- Works across **all metric ranges**, no matter how small or large  
- Ensures **visual consistency** with equal-width grading bands  
- Makes performance grading **clear and easy to understand**  

**💡 Use Case Example**

A score that ranges from **0–5** is normalized to a **1–5 scale**, and the result is plotted accordingly. Even if Grade 1 covers a huge part of the real range (e.g., 0–4), it appears as **just one equal segment** in the chart—just like every other grade. This makes it easier to visually compare and understand performance without bias from uneven value distribution.



