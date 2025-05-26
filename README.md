# Power-BI

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

