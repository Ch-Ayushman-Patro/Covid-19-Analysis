<div align="center">

# 🦠 Covid-19 Analysis

### Comprehensive Data Analysis of COVID-19 Pandemic Impact and Vaccination Trends

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive-purple.svg)](https://plotly.com/)

[Overview](#-overview) • [Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Datasets](#-datasets) • [Contact](#-contact)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Analysis Components](#-analysis-components)
- [Datasets](#-datasets)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Key Insights](#-key-insights)
- [Visualizations](#-visualizations)
- [Contributing](#-contributing)
- [Contact](#-contact)

---

## 🎯 Overview

This project presents a **comprehensive data analysis** of the COVID-19 pandemic, exploring multiple dimensions of the global health crisis. Through three detailed Jupyter notebooks, we analyze infection trends, pandemic impact, and vaccination progress across countries and time periods.

### Project Goals:
- 📊 **Track COVID-19 spread** and infection patterns globally
- 🌍 **Analyze pandemic impact** across different countries and regions
- 💉 **Monitor vaccination progress** and distribution worldwide
- 📈 **Visualize trends** using interactive charts and graphs
- 🔍 **Extract insights** from real-world pandemic data

---

## ✨ Features

### 📊 Multi-Dimensional Analysis
- **Infection Analysis**: Track cases, deaths, and recovery rates
- **Impact Assessment**: Understand pandemic effects across regions
- **Vaccination Tracking**: Monitor global vaccine distribution and progress

### 📈 Interactive Visualizations
- **Plotly Charts**: Interactive time-series and geographic visualizations
- **Statistical Plots**: Correlation analysis and distribution charts
- **Comparative Analysis**: Country-wise and region-wise comparisons

### 🔍 Data-Driven Insights
- **Trend Analysis**: Identify patterns in infection and vaccination rates
- **Geographic Patterns**: Understand regional variations
- **Temporal Trends**: Track changes over time

---

## 🧪 Analysis Components

### 1. 🦠 Covid-19 Analysis
**Main comprehensive analysis covering:**
- Global infection trends
- Country-wise case distribution
- Death and recovery rate analysis
- Time-series visualization of pandemic progression

### 2. 🌍 Covid-19 Impact Analysis
**Focused on pandemic impact:**
- Regional impact assessment
- Comparative country analysis
- Economic and social implications through data
- Severity metrics and trends

### 3. 💉 Covid-19 Vaccine Analysis
**Vaccination progress tracking:**
- Global vaccination rates
- Country-wise vaccine distribution
- Vaccination timeline analysis
- Vaccine type distribution
- Population coverage metrics

---

## 📊 Datasets

The project uses comprehensive COVID-19 datasets:

| Dataset | Description | Records |
|---------|-------------|---------|
| **raw_data.csv** | Raw COVID-19 infection data | Comprehensive global data |
| **transformed_data.csv** | Processed and cleaned data | Optimized for analysis |
| **country_vaccinations.csv** | Global vaccination statistics | Country-wise vaccine data |

### Data Sources:
- Official COVID-19 tracking databases
- World Health Organization (WHO) data
- Country-specific health ministry reports
- Global vaccination tracking initiatives

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Language** | ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python) |
| **Data Analysis** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn`, `plotly` |
| **Environment** | Jupyter Notebook |
| **Data Format** | CSV |

---

## 💻 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/Ch-Ayushman-Patro/Covid-19-Analysis.git
cd Covid-19-Analysis
```

2. **Install required packages:**
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Running the Analysis

1. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

2. **Open any analysis notebook:**
   - `Covid 19 Analysis.ipynb` - Main comprehensive analysis
   - `Covid 19 Impact Analysis.ipynb` - Impact-focused analysis
   - `Covid 19 Vaccine Analysis.ipynb` - Vaccination analysis

3. **Run the cells sequentially:**
   - Execute cells in order to reproduce the analysis
   - Interact with visualizations
   - Modify parameters to explore different aspects

### Analysis Workflow

```python
import pandas as pd
import plotly.express as px

# Load the data
df = pd.read_csv('transformed_data.csv')

# Quick overview
print(df.info())
print(df.describe())

# Create visualization
fig = px.line(df, x='date', y='cases', color='country')
fig.show()
```

---

## 📁 Project Structure

```
Covid-19-Analysis/
├── Covid 19 Analysis.ipynb           # Main comprehensive analysis
├── Covid 19 Impact Analysis.ipynb    # Pandemic impact analysis
├── Covid 19 Vaccine Analysis.ipynb   # Vaccination tracking analysis
├── Covid 19 Analysis.pdf             # PDF export of main analysis
├── raw_data.csv                      # Raw COVID-19 data
├── transformed_data.csv              # Processed data
├── country_vaccinations.csv          # Vaccination statistics
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
```

---

## 🔍 Key Insights

### 📊 Infection Trends
- Global case progression over time
- Peak infection periods identification
- Regional variation in spread patterns
- Recovery and mortality rate analysis

### 🌍 Geographic Patterns
- Country-wise infection density
- Regional hotspots identification
- Cross-border transmission patterns
- Healthcare system impact correlation

### 💉 Vaccination Progress
- Global vaccination rate trends
- Country-wise vaccine rollout speed
- Population coverage milestones
- Vaccine type distribution and effectiveness

---

## 📈 Visualizations

The project includes rich, interactive visualizations:

- 📉 **Time-Series Charts**: Track infection and vaccination trends over time
- 🗺️ **Geographic Maps**: Visualize global distribution and hotspots
- 📊 **Bar Charts**: Compare countries and regions
- 🥧 **Pie Charts**: Show distribution of cases, deaths, and vaccines
- 📈 **Line Graphs**: Display progression and trends
- 🔥 **Heatmaps**: Identify correlations and patterns

All visualizations are interactive (powered by Plotly) for better exploration.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch:** `git checkout -b feature/AmazingFeature`
3. **Commit your changes:** `git commit -m 'Add some AmazingFeature'`
4. **Push to the branch:** `git push origin feature/AmazingFeature`
5. **Open a Pull Request**

### Contribution Ideas:
- 📊 Additional analysis perspectives
- 🌍 Regional deep-dive studies
- 📈 Advanced statistical modeling
- 🎨 Enhanced visualizations
- 📝 Documentation improvements
- 🔄 Automated data updates

---

## 📬 Contact

**Developed by Ch Ayushman Patro**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/ch-ayushman-patro)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/Ch-Ayushman-Patro)

For questions, suggestions, or collaboration opportunities, feel free to reach out!

---

<div align="center">

**Made with 📊 and 🐍 Python**

*Stay safe, stay informed* 🦠💉

</div>
