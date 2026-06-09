# 📉 Unemployment Analysis (1991–2021)
**CodeAlpha Data Science Internship | Task 2**

---

## 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA) and Time-Series Analysis** on global unemployment data spanning **31 years (1991–2021)**. The goal is to uncover trends, identify the impact of major global events like **COVID-19**, and derive **policy-relevant insights** using Python-based data visualization tools.

---

## 📂 Dataset

- **Source:** `unemployment dataset.zip` (contains `unemployment analysis.csv`)
- **Format:** Wide format — each year is a separate column
- **Coverage:** Multiple countries, 1991 to 2021
- **Features:**

  | Column | Description |
  |---|---|
  | `Country Name` | Name of the country |
  | `Country Code` | ISO country code |
  | `1991–2021` | Unemployment rate (%) per year |

---

## 🛠️ Tech Stack

- **Python 3**
- **pandas** – Data loading, preprocessing & transformation
- **matplotlib** – Plotting and visualization
- **seaborn** – Statistical data visualization
- **Google Colab** – Development environment

---

## 🔄 Data Preprocessing & Transformation

- Mounted Google Drive and extracted dataset from ZIP file
- Removed duplicate rows
- Checked and confirmed no null values
- **Melted** the wide-format DataFrame into long format with `Year` and `Unemployment Rate` columns for time-series analysis

---

## 📊 Analysis Performed

### 1. Descriptive Statistics & Overall Trend
- Calculated global average unemployment rate per year
- Line plot showing the overall trend from 1991 to 2021

### 2. Country-Specific Analysis
- Identified **Top 5 highest** and **Top 5 lowest** average unemployment rate countries
- Side-by-side bar chart comparison

### 3. COVID-19 Impact Analysis
- Filtered data for 2019, 2020, 2021
- Visualized average unemployment spike during the pandemic
- Calculated % change per country (2019→2020 and 2020→2021)
- Identified countries with the largest COVID-19 unemployment surge and recovery

### 4. Year-over-Year Change
- Computed YoY % change in average global unemployment
- Line plot highlighting years with the biggest rises and drops

### 5. Decadal Distribution
- Added `Decade` column (1990s, 2000s, 2010s, 2020s)
- Box plots comparing unemployment distribution across decades

### 6. Policy-Relevant Insights
- **Insight 1:** Persistent extreme unemployment — structural policy recommendations
- **Insight 2:** Varied COVID-19 impact across countries (Panama, US, Qatar, Georgia)
- **Insight 3:** Long-term decadal shifts and cyclical economic patterns

---

## 🔍 Key Findings

- **COVID-19 (2020)** caused the sharpest single-year spike in global unemployment in the dataset
- Countries like **Panama** saw the largest unemployment surge during the pandemic
- **Qatar** and similar Gulf states consistently maintained some of the world's lowest unemployment rates
- The **2010s** showed a general improvement in global unemployment before the 2020 disruption
- Petal-level separation is an EDA classic — here, **year and country** are the most discriminative dimensions

---

## 🚀 How to Run

1. Upload `unemployment dataset.zip` to your **Google Drive**
2. Open `code_alpha_task2.ipynb` in **Google Colab**
3. Mount Drive when prompted
4. Run all cells in order (`Runtime > Run all`)

### Dependencies

```bash
pip install pandas matplotlib seaborn
```

---

## 📁 Project Structure

```
├── code_alpha_task2.ipynb       # Main analysis notebook
├── unemployment dataset.zip     # Raw dataset (zipped CSV)
└── README.md                    # Project documentation
```

---

## 👤 Author

**Aqsa Irfan**
CodeAlpha Data Science Internship | Task 2 – Unemployment Analysis
