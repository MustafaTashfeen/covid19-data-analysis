# Global COVID-19 Data Analysis & Visualization

A comprehensive data analysis and visualization program written in Python to examine global time-series COVID-19 dataset. This project processes daily confirmed case counts from around the world, cleans incomplete state data, calculates global trends, and identifies the most affected countries.

---

## 📌 Project Overview

This project was developed for the course **Programming for Business (CS2016)** at the **National University of Computer and Emerging Sciences (FAST-NUCES)**.

### Key Objectives:
- **Data Loading & Cleaning**: Handle missing entries, fill `Province/State` blanks with `"Unknown"`, zero-fill missing numeric values, and eliminate duplicate records.
- **Exploratory Data Analysis**: Inspect data shapes, column types, statistical summaries, and memory usage.
- **Global Trend Analysis**: Aggregate regional data to plot total confirmed cases worldwide over time.
- **Country Rankings**: Identify and visualize top affected countries using custom grouping and Seaborn bar charts.
- **Statistical Measures**: Compute mean, median, standard deviation, min, and max case counts across regions.

---

## 📂 Repository Contents

```text
├── covid19_analysis.ipynb                    # Primary Jupyter Notebook containing analysis & charts
├── time_series_covid19_confirmed_global.csv  # Global time-series dataset (Johns Hopkins University)
├── COVID19_Project_Report.docx               # Full project report document
└── README.md                                 # Project documentation
```

---

## 🛠️ Built With

- **Python 3.x**
- **Pandas**: Data manipulation, filtering, and aggregation (`pd.read_csv()`, `fillna()`, `groupby()`)
- **NumPy**: Numerical computations (`np.sum()`, `np.mean()`, `np.std()`)
- **Matplotlib**: Line plots for global case trajectories over time (`plt.plot()`)
- **Seaborn**: Aesthetic bar plots for top-country comparison (`sns.barplot()`)

---

## 📊 Key Findings & Results

- **Global Time Frame**: Analyzes daily case counts from January 22, 2020 through March 9, 2023 across 166+ countries and territories.
- **Top 5 Affected Countries by Cumulative Totals**:
  1. 🇮🇳 **India**
  2. 🇧🇷 **Brazil**
  3. 🇫🇷 **France**
  4. 🇩🇪 **Germany**
  5. 🇮🇹 **Italy**

---

## 👥 Authors & Credits

- **Mustafa Tashfeen** (24L-5592)
- **Imtanan Mujahid** (24L-5594)
- **Muhammad Sarmed** (24L-5530)
- **Suhaib Raza** (24L-5635)

**Course:** Programming for Business (CS2016) - Section 1D  
**Instructor:** Ms. Iman Ilyas  
**Institution:** National University of Computer and Emerging Sciences (FAST-NUCES)
