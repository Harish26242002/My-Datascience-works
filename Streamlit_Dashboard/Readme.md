# 📊 Portfolio Risk Dashboard

A **Streamlit-based interactive dashboard** to explore and monitor loan applications, borrower characteristics, and repayment outcomes.  
This dashboard provides a **360° view of portfolio health**, highlights potential risks, and supports **data-driven decision-making**.

---

## 🎯 Main Goal

The goal of this dashboard is to:
- Detect **default patterns** among borrowers.  
- Identify **high-risk borrower groups**.  
- Evaluate **data quality issues** in loan applications.  
- Support **credit policy and decision-making** with insights.  

---

## 🚀 Features

- **Global Filters**  
  Filter data by gender, education, housing, family status, income, and age.  

- **Multi-Page Navigation**  
  - 🏠 **Home** → Introduction, usage guide, and goals.  
  - 📊 **Overview & Data Quality** → Dataset summary, missing values, and KPIs.  
  - 👨‍👩‍👧 **Demographics & Household** → Borrower profiles (age, family, children).  
  - 💳 **Credit & Loan Behavior** → Loan size, income, credit ratios.  
  - 📈 **Risk Segmentation** → Compare defaulters vs. non-defaulters.  

- **Preprocessing Pipeline**  
  - Memory optimization  
  - Missing value treatment  
  - Feature engineering (Age, DTI, Loan-to-Income, etc.)  
  - Handling rare categories & winsorization  

- **Extra Features**  
  - 📌 KPI Cards for quick insights (Total Applicants, Default Rate, Repaid Rate).  
  - 📅 Time range and numeric sliders for deeper segmentation.  
  - 📑 Download filtered results as CSV.  
  - 🎨 Professional UI with icons and responsive layout.  

---

## 🧑‍💻 How to Use

1. **Run the App**  
   ```bash
   streamlit run home.py
   ```

2. **Open in Browser**  
   Go to [http://localhost:8501](http://localhost:8501)  

3. **Navigation**  
   - Use the sidebar to switch between pages.  
   - Apply global filters (gender, age, education, housing, etc.) to refine results.  

4. **Load Dataset**  
   - Data is loaded from a **Google Drive link** via `utils/dataset.py`.  
   - Replace the link with your own if required.  

---

## 📊 Key Insights You’ll Get

By using this dashboard, you’ll be able to answer questions like:
- 📈 What is the **overall default rate** in the portfolio?  
- 👨‍👩‍👧 How do **demographics (age, family, education)** affect risk?  
- 💳 What role does **income, loan size, and credit behavior** play in defaults?  
- ⚠️ What are the **early warning indicators** of risk?  

---

## 📂 Project Structure

```
├── home.py                 # Streamlit Home Page (intro, usage, goals)
├── preprocessing.py        # Data preprocessing & global filters
├── utils/
│   └── dataset.py          # Custom load_data function (loads from Drive link)
├── pages/
│   ├── 1_Overview.py       # Dataset quality & KPIs
│   ├── 2_Credit.py         # Credit & loan analysis
│   ├── 3_Demographics.py   # Demographics & household profile
│   ├── 4_Risk.py           # Risk segmentation
├── practice.ipynb          # Practice notebook for testing analysis
└── README.md               # Project documentation
```

---

## 📦 Requirements

- Python 3.8+  
- Streamlit  
- Pandas, NumPy, Matplotlib, SciPy  

Install via:
```bash
pip install streamlit pandas numpy matplotlib scipy
```

---

## 📌 Notes

- Replace the **Google Drive link** in `utils/dataset.py` with your own if the original is inaccessible.  
- Ensure the Drive file is shared with *"Anyone with the link"* for proper loading.  

---

💡 *Tip: Use filters to compare defaulters vs. non-defaulters and uncover risk patterns quickly!*