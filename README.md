# 📊 E-Commerce Revenue Analysis & Automated Data Pipeline
An end-to-end Python script built with **Pandas** and **Matplotlib** that ingests raw e-commerce transaction data, cleans string-formatted currency values, handles missing values, and visualizes top revenue-generating products.

---

## 🚀 Key Features & Workflow

1. **Automated Data Ingestion:** Loads raw transaction data (`.tsv` format) directly from web sources.
2. **Defensive Data Cleaning:** 
   - Detects string data types in currency columns.
   - Strips non-numeric characters (`$`) and converts values to `float`.
   - Handles missing descriptions by filling `NaN` values with standard fallbacks.
3. **Feature Engineering:** Calculates total line-item revenue (`quantity` × `item_price`).
4. **Aggregation & Visualization:** Groups totals by item name and generates a clean, formatted bar chart showing top revenue drivers.

---

## 📈 Visual Output

<img width="630" height="470" alt="Top 5 Revenue Generators bar Graph" src="https://github.com/user-attachments/assets/f9a31c5b-0e3e-4c71-b319-1044baed18ed" />

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3
- **Data Manipulation:** `pandas`
- **Visualization:** `matplotlib`
