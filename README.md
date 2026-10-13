# fnp-excel-sales-analysis
Interactive sales and delivery dashboard for Ferns N Petals (Excel)

# 🌸 Ferns N Petals (FNP) - Sales & Gifting Analytics Dashboard (Excel)

## 📌 Project Overview
Ferns N Petals (FNP) India ka leading gifting platform hai jo alag-alag occasions (Diwali, Rakhi, Valentine's Day, Birthdays) ke liye gifts deliver karta hai. 

Is project me **Kaggle ke FNP e-commerce dataset** ka use karke customer purchase behavior, seasonal demand, city-wise sales, aur delivery efficiency ko analyze karke ek **Interactive Microsoft Excel Dashboard** design kiya gaya hai.

---

## 📊 Dashboard Preview
![Dashboard Preview](FNP%20Dashboard.png)

---

## 📂 Dataset Source & Architecture
- **Source:** Kaggle (Ferns N Petals Gifting & E-commerce Dataset)
- **Data Model:** Relational / Star Schema jisme multiple tables ko connect karke analyze kiya gaya:
  - `orders`: Order ID, Customer ID, Product ID, Order Date, Delivery Date, Quantity
  - `products`: Product ID, Product Name, Category, Price, Occasion
  - `customers`: Customer ID, Customer Name, City, State

---

## 🛠️ Excel Skills & Techniques Used
- **Data Cleaning & ETL:** Power Query ka use karke duplicates remove kiye, text format normalize kiya, aur missing dates handle kiye.
- **Calculated Metrics (Formulas):**
  - Delivery Lead Time: `[Delivery Date] - [Order Date]`
  - Total Revenue, Average Order Value (AOV), aur Customer Lifetime Spending.
  - `XLOOKUP`, `INDEX-MATCH`, `SUMIFS`, `COUNTIFS`.
- **Data Modeling & Pivot Tables:** Multi-table relationships, dynamic summary tables, aur date hierarchies.
- **Interactive UI:** Slicers (Year, Occasion, Category, City), KPI metric cards, aur custom charts.

---

## 🎯 Key Business Questions Answered
1. **Revenue & Orders:** Total revenue kitna generate hua aur Average Order Value (AOV) kya hai?
2. **Occasion & Seasonality:** Kaunse festive occasions (Holi, Raksha Bandhan, Valentine's Day) par sales peak hoti hai?
3. **Category Breakdown:** Top-performing categories kaunsi hain (Soft Toys, Sweets, Combos, Gifts)?
4. **Geography & Logistics:** Kaunse cities se maximum orders aate hain, aur average delivery turnaround time kitna lagta hai?

---

## 💡 Key Business Insights
- **Seasonal Spikes:** Valentine's Day aur Raksha Bandhan ke aas-paas orders aur revenue me significant surge dekhne ko milta hai.
- **Top Categories:** Emotional gifting categories jaise Soft Toys, Personalized Hampers, aur Sweets total revenue me sabse bada share contribute karte hain.
- **Delivery Lead Time:** Average order fulfillment time lagbhag 5-6 days ka hai; high-volume cities me regional warehousing logistics time ko reduce kar sakti hai.
- **City Penetration:** Tier-2 aur regional cities me high order volumes identify hue, jo targeted marketing ke liye high-potential areas hain.

---

## 📁 Repository Files
- `fnp_sales_analysis.xlsx` : Complete Excel workbook jisme raw data sheets, working Pivot calculations, aur dynamic dashboard integrated hai.
- `FNP Dashboard.png` : High-resolution preview of the finalized dashboard.
