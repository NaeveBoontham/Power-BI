# Power-BI
<br>  

# 🔐 **Row-Level & Page-Level Security in Power BI**

**📁 Overview**

This Power BI project showcases how to implement **Row-Level Security (RLS)** and **Page-Level Security (PLS)** to control both **data visibility** and **report page access** based on department and role.

The report uses:  
- **RLS** to restrict which employee records users can see  
- **PLS** to limit access to specific pages within the report

**✅ Benefits**

- Enforces strict data access without duplicating reports  
- Ensures each user sees **only the data they’re allowed to**  
- Built using native Power BI features — no external tools needed  
- Scalable to multiple departments and role levels

**💡 Use Case Example**

The dataset contains employee records from **8 departments**:  
`HR, Legal, Support, Marketing, Operations, Sales, IT, Finance`  
Each department includes two roles: `Lead` and `Staff`.

The report has two pages:  
- `All View`  
- `HR View Filter`

The security setup enforces:  
- **HR users** can access **both pages**  
- **Other departments** can only view the **All View** page  
- **Leads** can see all staff in their department — but **not other leads**  
- **Staff** can only view **their own record**

<br>

![Pic](https://github.com/NaeveBoontham/Power-BI/blob/cada137944008c913bc4564f95e965db5dd73789/RLS%26PLS/RLS%26PLS.png)

[Download PBIX file](https://github.com/NaeveBoontham/Power-BI/tree/main/RLS%26PLS)

---
<br>

# 📊 Dynamic Latest Month Filtering in Power BI

**📁 Overview**

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

<br>

![Pic](https://github.com/NaeveBoontham/Power-BI/blob/bd8603fed5f5913374d4ee8cae330fd64521fa8c/LastestMonthFilter/LastestMonthFilter.png)

[Download PBIX file](https://github.com/NaeveBoontham/Power-BI/tree/main/LastestMonthFilter)

---
<br>

# 📈 Cumulative Monthly Filtering in Power BI

**📁 Overview**

This Power BI report showcases a method to **dynamically display data from the beginning of a selected year up to a user-selected month**. It meets a common business requirement: instead of filtering to just a single month, users want to see the **cumulative values from January to the selected month**.

**✅ Benefits**

- Gives users intuitive control over how much of the year’s data they want to see  
- Enables powerful **year-to-date** or **partial period comparisons**  
- Makes the report more **user-friendly and dynamic**

**💡 Use Case Example**

If the user selects **Year = 2020** and **Month = August**, the report will display data from **January to August 2020**, rather than just August.

<br>

![Pic](https://github.com/NaeveBoontham/Power-BI/blob/bd8603fed5f5913374d4ee8cae330fd64521fa8c/CumulativeMonthFilter/CumulativeMonthFilter.png)

[Download PBIX file](https://github.com/NaeveBoontham/Power-BI/tree/main/CumulativeMonthFilter)

---
<br>

# 📊 Linear Gauge with Normalized Grading in Power BI

**📁 Overview**

In this project, I built a **linear gauge-style bar chart** in Power BI to visualize performance metrics by grading them from **Grade 1 (lowest)** to **Grade 5 (highest)**. This was based on real user requirements where each metric had **non-uniform and varying value ranges**, making traditional charting methods ineffective.

**✅ Benefits**

- Works across **all metric ranges**, no matter how small or large  
- Ensures **visual consistency** with equal-width grading bands  
- Makes performance grading **clear and easy to understand**  

**💡 Use Case Example**

A score that ranges from **0–5** is normalized to a **1–5 scale**, and the result is plotted accordingly. Even if Grade 1 covers a huge part of the real range (e.g., 0–4), it appears as **just one equal segment** in the chart—just like every other grade. This makes it easier to visually compare and understand performance without bias from uneven value distribution.

<br>

![Pic](https://github.com/NaeveBoontham/Power-BI/blob/bd8603fed5f5913374d4ee8cae330fd64521fa8c/LinearGauge/LinearGauge.png)

[Download PBIX file](https://github.com/NaeveBoontham/Power-BI/tree/main/LinearGauge)

---
<br>

# 📊 Progress Bar with Conditional Grading in Power BI

**📁 Overview**

This Power BI project is designed to visualize progress toward a target using a **stacked bar chart** that shows:
- The **achieved value**
- The **remaining value**
- And conditionally **color-codes** the progress bar based on how far along you are toward the goal.

**✅ Benefits**

- Simulates **dynamic conditional coloring** using stacked bars
- Works within Power BI’s native capabilities
- **No custom visuals or extensions** needed
- Reusable for **targets in sales, production, operations, or performance tracking**

**💡 Use Case Example**

A business team requested a visual progress bar to track performance toward a target (e.g., 75,000). The bar needed to:

- Show both **achieved** and **remaining** values side-by-side  
- **Change color** based on progress:
  - 🔴 Low (0–35,000)
  - 🟡 Medium (35,000–target)
  - 🟢 Over target
- Use ⚫ gray to represent the remaining portion

Since Power BI doesn’t support conditional formatting in stacked bars, the solution splits the achieved value into ranges using DAX and applies fixed colors—mimicking dynamic progress grading.

<br>

![Pic](https://github.com/NaeveBoontham/Power-BI/blob/ca3be4aa047e533e325f5d7f3bf19fea20958d24/ProgressBar%26Dot/ProgressBarDot.png)

[Download PBIX file](https://github.com/NaeveBoontham/Power-BI/tree/main/ProgressBar%26Dot)






