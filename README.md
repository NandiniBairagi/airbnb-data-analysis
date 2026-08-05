# airbnb-data-analysis
End-to-end data cleaning, feature engineering, and exploratory data analysis of NYC Airbnb listings using Python.
# 🏙️ NYC Airbnb Data Analysis & Price Exploration

An end-to-end Data Analytics project analyzing 83,000+ Airbnb listings in New York City. This repository covers data ingestion, rigorous data cleaning, string parsing, feature engineering, and exploratory data analysis (EDA) using Python.

---

## 📌 Project Overview
The goal of this analysis is to evaluate pricing distributions, host behaviors, and availability trends across different New York City boroughs. Raw real-world datasets often contain missing values, inconsistent formats, and outliers. This project demonstrates standard Data Operations pipelines to transform unrefined data into actionable insights.

---

## 🛠️ Tech Stack & Tools
* **Programming Language**: Python
* **Data Processing**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Environment**: Jupyter Notebook
* **Text / String Operations**: Regular Expressions (Regex)

---

## ⚙️ Key Workflow & Steps

### 1. Data Cleaning & Normalization
* Handled missing value strategies across major demographic and listing attributes.
* Deduplicated records to ensure accurate dataset integrity across 83,000+ rows.
* Converted datetime variables and numeric formats.

### 2. Feature Engineering & String Parsing
* Extracted numeric listing prices from string formats containing symbols (e.g., `$150.00` ➔ `150.0`) using **Regex**.
* Categorized data types across categorical variables and boolean indicators.

### 3. Exploratory Data Analysis (EDA)
* Computed descriptive statistics to inspect distributional skewness, spread, and central tendencies.
* Evaluated pricing trends based on neighborhood groupings (Manhattan, Brooklyn, Queens, etc.).
* Analyzed review frequency and host availability patterns.

---

## 📊 Key Insights
* **Price Variance**: Significant price disparity observed across boroughs, with Manhattan maintaining the highest median listing price.
* **Minimum Stay Impact**: Identified extreme outliers in minimum night requirements, isolating short-term vs. long-term listing strategies.
* **Availability Trends**: Uncovered correlation patterns between review counts and host responsiveness/availability metrics.

---

## 🚀 How to Run Locally

1. **Clone this repository**:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/airbnb-data-analysis-nyc.git](https://github.com/YOUR_USERNAME/airbnb-data-analysis-nyc.git)
   cd airbnb-data-analysis-nyc
2. **Install required repository**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook airbnb_analysis.ipynb

👩‍💻 Author

Nandini Bairagi

If you found this project useful, feel free to ⭐ the repository.
LinkedIn: https://www.linkedin.com/in/nandinibairagi
   
