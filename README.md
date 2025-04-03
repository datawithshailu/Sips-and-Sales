# Sips-and-Sales
The Sips and Sales dashboard is an interactive Excel-based sales analysis tool designed specifically for coffee shop sales. It provides valuable insights into sales performance across various dimensions, helping coffee shop owners and managers track key metrics, identify trends, and optimize decision-making.

# **Sips and Sales - Coffee Shop Sales Dashboard ☕📊**

## **Process Steps**

### **1️⃣ Data Extraction & Transformation**
- Extracted the sales data file and loaded it into **Power Query Editor**.
- **Cleaned Data:**
  - Removed unnecessary white spaces using the **Trim** function.
  - Standardized **Transaction Time**, as it contained both date and time.
  - Extracted **quantity categories** (Large, Medium, Small) from the **Product Details** column using **Conditional Columns**.
  - Replaced certain values in the **Product Details** column for consistency.
- **Created a Custom Column:**
  - `Total Bill = Unit Price * Transaction Quantity`

### **2️⃣ Feature Engineering**
- Extracted **Day of the Week, Month Name, and Hour** from **Transaction Date & Time** to analyze sales trends based on time.
- Closed & loaded the cleaned data into Excel.

---

## **3️⃣ Pivot Table Creation**

Built multiple Pivot Tables for sales insights:

1. **Hour vs. Sum of Transaction Quantity** → Sales volume by hour.
2. **Day Name vs. Sum of Total Bill** → Sales by day of the week.
3. **Month Name vs. Sum of Total Bill** → Sales by month.
4. **Product Category vs. Total Bill** → Revenue breakdown by category.
5. **Product Type vs. Total Bill (Top 5)** → Best-selling product types.
6. **Store Location vs. Total Bill (Top 5)** → Best-performing store locations.
7. **Store Location vs. Count of Transaction ID (Top 5)** → Footfall analysis by store.
8. **Product Detail vs. Total Bill (Top 5)** → Top-selling specific products.

---

## **4️⃣ Sorting & Enhancements**
- **Sorted Day & Month in Order:**
  - Added **Day of the Week (Number)** and **Month Number** in Power Query Editor.
  - Loaded it into **Power Pivot** and sorted Month Name by Month Number & Day Name by Day Number.
- Used **custom coffee-themed color codes** to enhance the dashboard’s visualization.
- Added **slicers** for Month-wise & Day-wise filtering.
- **Protected the sheet** to prevent accidental modifications.

---

## **5️⃣ Final Deliverables**
- **Interactive Dashboard** with visual insights.
- Easy-to-use **slicers & filters** for better analysis.
- **Sales trends breakdown** by time, location, and product categories.
- **Optimized and cleaned dataset** for efficient reporting.

---

## **Future Enhancements 🚀**
✅ **Power BI Integration** for advanced data visualization.  
✅ **Automated Data Refresh** to keep reports up-to-date.  
✅ **Predictive Sales Analysis** using machine learning.  

---

### 💡 **Feel free to contribute, suggest improvements, or reach out for collaboration!** 😃
