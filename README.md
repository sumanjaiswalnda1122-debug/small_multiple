# Power BI Small Multiples Assignment

This project demonstrates the use of **Small Multiples** in Power BI to compare sales performance across Regions, Categories, and Sales Persons.

## 📁 Project Files

| File | Description |
|---|---|
| `Small_Multiples_PowerBI_Assignment_Data.xlsx` | Source dataset (`Sales_Data` sheet) with fields: Date, Region, Category, Sub_Category, Sales_Person, Sales, Quantity, Profit |
| `small_multiples.pbix` | Power BI report file containing the built visuals |
| `__Assignment_Objective_SMALL_MULTIPLE_.pdf` | Assignment brief (objectives and questions) |
| `small_multiple.docx` | Write-up with answers to each assignment question |

## 🎯 Objective

Learn how to use Small Multiples in Power BI to compare performance across:
- Regions
- Categories
- Sales Persons

## 📊 Data Model

Single flat table **Sales_Data** with the following columns:

`Date | Region | Category | Sub_Category | Sales_Person | Sales | Quantity | Profit`

Data covers transactions dated in **January 2025**.

## ✅ Tasks & Findings

### Q1 — Basic Small Multiples
Clustered column chart (Axis: Category, Values: Sum of Sales) split by Small Multiple field **Region**.
- **Finding:** North and East had the highest sales for Electronics.

### Q2 — Sales Trend Using Small Multiples
Line chart (X-axis: Date, Y-axis: Sum of Sales) split by Small Multiple field **Category**.
- **Finding:** Electronics showed the most consistent sales trend.

### Q3 — Profit Comparison
Bar chart (Axis: Sales_Person, Values: Sum of Profit) split by Small Multiple field **Region**.
- **Finding:** Best regional performers — Amit in North (₹148K), Ravi in South, Suresh in West, Neha in East.

### Q4 — Quantity Analysis
Column chart (Axis: Sub_Category, Values: Sum of Quantity) split by Small Multiple field **Category**.
- **Finding:**
  - Electronics → Mobile leads (15 units)
  - Furniture → Chair leads (10 units)
  - Office Supplies → Pen leads (110 units)

### Q5 — Advanced Task (Formatting & Filtering)
Adjusted grid layout, title alignment, and enabled data labels; applied a report-level filter for **January 2025**.
- **Finding:** Filters apply uniformly across all small multiple visuals, keeping every panel synchronized to the same filter context, which makes cross-panel comparison much easier since all data is drawn from the same time window.

## 🧠 Key Learning Outcomes

- Understand Small Multiples vs. normal charts
- Compare performance visually without slicers
- Improve dashboard readability
- Practice formatting & filtering with Small Multiples

## ▶️ How to Use

1. Open `Small_Multiples_PowerBI_Assignment_Data.xlsx` to review the raw dataset.
2. Open `small_multiples.pbix` in Power BI Desktop to view/interact with the report.
3. Refer to `small_multiple.docx` for the full written answers to each assignment question.
