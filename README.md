📊 Power BI Dashboards

Project 1 — Superstore Sales & Profitability Dashboard

<img width="1365" height="772" alt="image" src="https://github.com/user-attachments/assets/54b67300-bf65-44f3-bbf9-a88a734ecd5d" />


📌 Objective
Analyze sales and profitability patterns in a retail superstore 
dataset to identify loss-making segments.

🔍 Key Insights
- Total Profit: $286.40K with hidden losses of -$156.13K
- 54% of profits offset by losses in 3 sub-categories
- Binders (37%), Machines (30%), Tables (26%) — highest 
  average discounts → highest losses
- Fasteners at 7.85% discount → minimal losses
- Clear pattern: discounts above 25% consistently lead 
  to unprofitable sales

🛠️ Tools & Skills Used
- Power BI Desktop
- Power Query (data cleaning, fixing data types)
- DAX Measures:
  - Total Profit = SUM
  - Loss Amount = CALCULATE with filter
  - Loss % of Profit = DIVIDE
  - Average Discount = AVERAGE
- Interactive slicers (Region, Category)

### 📁 Dataset
Sample Superstore Dataset — Kaggle
