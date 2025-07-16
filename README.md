# Data Analysis Projects

This repository contains two practical data analysis projects that demonstrate **data extraction, cleaning, visualization, profiling, and API-based data collection**.

## 📂 Projects Overview

### 1. Exploratory Data Analysis (EDA)

**Folder:** `EDA/`

#### Description

This project implements a complete **Exploratory Data Analysis (EDA)** workflow. It helps in summarizing datasets, identifying patterns, and uncovering relationships.

**Key tasks:**

- **Data Extraction:** Load datasets from CSV, Excel, or online sources.
- **Data Cleaning:**  
  - Handle missing values  
  - Fix incorrect data types  
  - Remove duplicates  
  - Manage outliers
- **Visualization:** Use graphical tools to explore data:  
  - Histograms  
  - Boxplots  
  - Correlation heatmaps  
  - Bar charts
- **Data Profiling:** Automatically generate comprehensive data reports.
- **Insights:** Extract actionable insights from the dataset.

#### Tools & Libraries

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- **ydata-profiling** (for automated data profiling reports)
- Jupyter Notebooks

---

### 2. Weather Analysis with API

**Folder:** `Weather/`

#### Description

This project focuses on **real-time weather data analysis** using external APIs (e.g., **OpenWeatherMap**).

**Key tasks:**

- **Data Extraction:** Fetch current or historical weather data via API.
- **Data Processing:** Convert JSON responses to structured **DataFrames**.
- **Data Storage:** Save the weather data into **CSV files** for further use.
- **Visualization:** Create informative visual reports for:  
  - Temperature trends  
  - Humidity patterns  
  - Wind speed analysis
- **Use Case:** Compare weather conditions across cities or monitor weather changes over time.

#### Tools & Libraries

- Python
- `requests` (for API calls)
- Pandas
- Matplotlib, Seaborn, Plotly
- Jupyter Notebooks

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/Akash-N1406/Data-Analysis.git
cd Data-Analysis
