<div align="center">

# 📊 Retail Sales Data Analysis & Insights

### Uncovering Business Intelligence from 12 Months of Electronics Store Sales

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)

---

*Transforming raw sales data into actionable business insights*

</div>

---

## 🎯 Project Overview

This project leverages **Python Pandas** and **Matplotlib** to analyze and answer critical business questions using 12 months of real-world sales data. The dataset contains **hundreds of thousands of electronics store purchases**, broken down by month, product type, cost, purchase address, and more.

---

## 📁 Dataset

| Feature | Description |
|---------|-------------|
| **Order ID** | Unique identifier for each order |
| **Product** | Name of the product sold |
| **Quantity Ordered** | Number of units purchased |
| **Price Each** | Price per unit ($) |
| **Order Date** | Date and time of purchase |
| **Purchase Address** | Full address including city and state |

### 📅 Data Coverage
```
📦 12 Monthly CSV Files (January 2019 - December 2019)
📍 9 Major US Cities
🛒 18+ Product Categories
💰 Hundreds of Thousands of Transactions
```

---

## 🧹 Data Cleaning

Before diving into analysis, the data underwent thorough cleaning:

| Task | Method |
|------|--------|
| 🗑️ Remove missing values | `dropna()` |
| 🚫 Filter invalid rows | Conditional filtering |
| 🔄 Type conversion | `to_numeric()`, `to_datetime()`, `astype()` |
| ➕ Feature engineering | Extract month, city, hour from existing columns |

---

## ❓ Business Questions Explored

### 1️⃣ What was the best month for sales?
> *Identifying peak revenue periods and seasonal trends*

### 2️⃣ Which city sold the most products?
> *Geographic analysis for targeted marketing*

### 3️⃣ What time should we display advertisements?
> *Optimizing ad timing to maximize customer engagement*

### 4️⃣ What products are most often sold together?
> *Market basket analysis for bundle recommendations*

### 5️⃣ What product sold the most and why?
> *Understanding product performance and pricing strategies*

---

## 🛠️ Technical Implementation

### Libraries Used
```python
import pandas as pd
import matplotlib.pyplot as plt
from itertools import combinations
from collections import Counter
```

### Key Techniques

| Technique | Purpose |
|-----------|---------|
| `pd.concat()` | Merge 12 monthly CSV files |
| `.str` accessor | Parse strings for new columns |
| `.apply()` | Custom transformations |
| `.groupby()` | Aggregate analysis |
| `plt.bar()` / `plt.plot()` | Data visualization |

---

## 📈 Sample Insights

```
📊 Best Sales Month: December (Holiday Season!)
🏙️ Top Performing City: San Francisco, CA
⏰ Peak Shopping Hours: 11 AM & 7 PM
🔗 Popular Bundle: iPhone + Lightning Charging Cable
🏆 Best-Selling Product: AAA Batteries (High volume, low price)
```

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas matplotlib jupyter
```

### Running the Analysis
```bash
# Clone the repository
git clone https://github.com/Shubham-Raj-1503/Retail-Sales-Data-Analysis.git

# Navigate to the project directory
cd Retail-Sales-Data-Analysis

# Launch Jupyter Notebook
jupyter notebook "Retail Sales Data Analysis & Insights Using Python.ipynb"
```

---

## 📂 Project Structure

```
📦 Retail-Sales-Data-Analysis
├── 📓 Retail Sales Data Analysis & Insights Using Python.ipynb
├── 📄 README.md
├── 📁 allmonthssales/          # Combined data output
└── 📊 Sales Data Files
    ├── Sales_January_2019.csv
    ├── Sales_February_2019.csv
    ├── Sales_March_2019.csv
    ├── Sales_April_2019.csv
    ├── Sales_May_2019.csv
    ├── Sales_June_2019.csv
    ├── Sales_July_2019.csv
    ├── Sales_August_2019.csv
    ├── Sales_September_2019.csv
    ├── Sales_October_2019.csv
    ├── Sales_November_2019.csv
    └── Sales_December_2019.csv
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

Made with ❤️ and Python

</div>
