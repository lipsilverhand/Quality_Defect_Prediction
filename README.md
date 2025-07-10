# **Quality Defect Analysis Dashboard and Storytelling (2023 - 2024)**

This project analyzes procurement and supplier data to identify defect trends and predict high-risk purchase orders.  
Combining Python machine learning and Tableau dashboards, it helps procurement and quality teams make proactive, data-driven decisions.

### Tools and Framework
#### Tools: Python, Tableau, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Random Forest, Jupiter Notebook, VScode, Excel
#### Framework: PAIR model (Problem → Approach → Insights → Recommendations)

---

## 🔍 Problem

Procurement teams often struggle with hidden defect risks in purchase orders. Manual reviews miss supplier trends and root causes, resulting in poor quality, delays, and increased costs.

---

## 🔧 Approach

### 🛠 Tools:
- **Python:** Data cleaning, exploration, Random Forest defect prediction
- **Tableau:** Dashboard visualization and defect trend analysis
- **Pandas, Scikit-learn, Seaborn:** Data wrangling and model building

### 🔗 Workflow:
1. **Data Analysis & Modeling (Python)**
   - Cleaned order data
   - Explored defect rates by supplier and product
   - Built a Random Forest Classifier to predict defective POs
   - Extracted feature importance

2. **Business Dashboard (Tableau)**
   - KPI cards for defect rate, total defective units, order count, and lead time
   - Line chart showing defect rate trends by year
   - Bar chart showing defect rate by supplier
   - Feature Importance chart explaining defect root causes
   - Pie chart for Defective vs Non-Defective orders
   - Drill-down report by Item ID and year

### Overview Dashboard: [View Dashboard Link](https://public.tableau.com/app/profile/phuoc.huynh7023/viz/Book1_17521801585140/Dashboard1)
<img width="1295" height="597" alt="{05C0228D-3AC0-42D7-B649-6B9883F8D822}" src="https://github.com/user-attachments/assets/d7189b78-75ad-4fe5-912f-e1c42bd230a7" />
<img width="1299" height="594" alt="{C1F579C7-A4C8-4388-A98E-0DB68F16EF88}" src="https://github.com/user-attachments/assets/a6ab0262-4066-4337-8260-d70c1c7d4122" />




---

## 📊 Key Insights

| KPI                    | Value |
|------------------------|-------|
| Defect Rate (%)         | 66.2% |
| Total Defective Units   | 483   |
| Total Orders            | 25,647|
| Avg. Lead Time (days)   | 10    |
| Total Price ($)         | 135,746|

- **SUP-002 and SUP-003** are the highest defect-rate suppliers (~70%+)
- Defect trends fluctuate significantly month to month
- Root causes: supplier rating, unit price, and order quantity, not compliance flag

---

## ✅ Recommendations

- Improve procurement controls on high-risk suppliers
- Optimize order quantity and lead time to reduce rush defects
- Enhance supplier rating system to reflect quality performance

---

