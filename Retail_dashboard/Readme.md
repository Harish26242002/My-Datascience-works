# 🛍️ Superstore Sales Analysis Dashboard

An interactive **Streamlit dashboard** for analyzing sales, profit, and regional performance of a **Superstore dataset**.  
This dashboard provides actionable insights through **visualizations, KPIs, and filters**, helping you quickly explore trends and identify growth opportunities.

---

## 🎯 Main Goal

The goal of this dashboard is to:
- Understand **sales & profit trends** over time.
- Identify **top-performing regions, categories, and products**.
- Compare profitability and sales contributions.
- Provide a flexible platform where you can **upload your own dataset**.

---

## 🚀 Features

- 📊 **Overview Dashboard** – Key metrics, KPIs, and quick insights  
- 🛒 **Sales Analysis** – Sales trends across products, categories, and time  
- 💰 **Profit Analysis** – Profitability drivers and cost optimization areas  
- 🌍 **Region Analysis** – Regional breakdown of performance  
- 📦 **Category Analysis** – Category & subcategory contributions  
- 📂 **Upload Support** – Upload your own `.csv` or `.xls/.xlsx` files  
- 🔍 **Interactive Filters** – Slice & dice data by time, region, and category  
- 🎨 **Modern UI** – Clean layout, icons, and well-structured visuals  

---

## 🧑‍💻 How to Use

1. **Run the App**  
   ```bash
   streamlit run Home.py
   ```

2. **Open in Browser**  
   Go to [http://localhost:8501](http://localhost:8501)  

3. **Navigation**  
   - Use the **sidebar menu** to switch between pages (Overview, Sales, Profit, Region, Category).  
   - Apply **filters** (date range, region, category) to refine insights.  

4. **Upload Your Own Data**  
   - Use the **Upload Section** in the sidebar.  
   - Supported formats: `.csv`, `.xls`, `.xlsx`  

---

## 📊 Key Insights You’ll Get

By using this dashboard, you’ll be able to answer questions like:
- 📈 What are the **overall sales and profit trends**?  
- 🏆 Which **products and categories** drive the most revenue?  
- 🌍 How do **different regions** perform in terms of sales and profit?  
- 💡 Where are the **growth opportunities** for better profitability?  

---

## 📂 Project Structure

```
├── Home.py                 # Main Streamlit app entry point
├── utils/
│   └── load_data.py        # Data loading and preprocessing functions
├── Source Sales Data.xls   # Default sample dataset
├── requirments.txt         # Python dependencies
└── README.md               # Project documentation
```

---

## 📦 Requirements

- `streamlit`
- `pandas`
- `numpy`
- `matplotlib`
- `altair`
- `scikit-learn`
- `openpyxl`

Install with:
```bash
pip install -r requirments.txt
```

---

## 🌟 Extra Features & Good-to-Haves

- 📌 **KPI Cards** at the top for quick insights (Total Sales, Profit, Avg Order Value).  
- 📅 **Time Range Filters** for dynamic period-based analysis.  
- 🖼️ **Custom Color Themes** for a clean professional look.  
- 📑 **Download Reports** (CSV/Excel export of filtered data).  
- 🖥️ **Responsive Layout** that works well on both desktop & mobile.  

---

## ▶️ Example

Once the app runs, you’ll see an **Overview Dashboard** with KPIs like:
- Total Sales
- Total Profit
- Profit Margin (%)
- Top 5 Regions
- Category-wise breakdown  

---

💡 *Tip: Try uploading your own business sales data to explore customized insights!*