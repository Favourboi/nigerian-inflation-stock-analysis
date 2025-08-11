# Nigerian Inflation & Stock Market Analysis

This project analyzes trends in **Nigerian inflation (2003–2025)** and **stock market performance (2000–2025)** to explore possible relationships between the two.
It combines data from the **Central Bank of Nigeria (CBN)** and the **Nigerian Exchange (NGX)**, using Python for cleaning, visualization, and exploratory analysis.

---

## 📊 Datasets

* **CBN Inflation Measures (2003–2025)** — Headline, Core, and Food inflation rates.
* **NGX Stocks (2000–2025)** — Daily price and volume data for listed companies.
* **NGX Company List** — Company names and sectors for grouping stock performance.

---

## 🔍 Analysis Workflow

1. **Data Preparation**

   * Clean missing or inconsistent values.
   * Convert dates to `datetime` format.
   * Merge datasets for combined analysis.

2. **Exploratory Data Analysis**

   * Visualize inflation trends over time.
   * Track stock market performance.
   * Analyze performance by sector.

3. **Correlation Analysis**

   * Compare inflation rates with market returns.

---

## 📂 Project Structure

```
nigerian-inflation-stock-analysis/
│
├── data/
│   ├── CBN Inflation Measures (2003–2025).csv
│   ├── NGX Stocks 2000 - 2025.csv
│   └── ngx_company_list.csv
│
├── nigerian_inflation_stock_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone this repository

```bash
git clone https://github.com/yourusername/nigerian-inflation-stock-analysis.git
cd nigerian-inflation-stock-analysis
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Open Jupyter Notebook

```bash
jupyter notebook nigerian_inflation_stock_analysis.ipynb
```

---

## 🛠 Built With

* Python 3.x
* Pandas
* Matplotlib & Seaborn
* Jupyter Notebook

