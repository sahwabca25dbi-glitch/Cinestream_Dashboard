# 🎬 CineStream Content Analytics Dashboard

## 📌 Project Overview

The **CineStream Content Analytics Dashboard** is an interactive data visualization application developed using **Streamlit**. The project analyzes the content catalog of a fictional OTT streaming platform, **CineStream**, and provides business insights through interactive dashboards, KPIs, charts, and filters.

This dashboard enables users to explore content performance, analyze financial metrics, monitor audience engagement, and support business decision-making.

---

## 🎯 Objectives

The dashboard answers the following business questions:

- Which genres and languages generate the highest views, watch hours, and audience completion?
- Do high-budget productions provide better returns than smaller productions?
- How has the content mix changed over time?
- Which countries attract the highest number of subscribers?
- Do higher IMDb ratings lead to higher popularity?
- Which titles are making losses and what characteristics do they share?

---

## ✨ Features

- 📊 Interactive KPI Cards
- 🎛 Sidebar Filters
- 📅 Date Range Filter
- 🎨 Dynamic Chart Color Selection
- 📥 Download Filtered Data as CSV
- 📈 Interactive Visualizations
- 💰 Revenue & ROI Analysis
- 🎬 Genre & Language Analysis
- ⭐ IMDb Performance Analysis
- 🚨 Quality Alert Indicators
- ⚡ Cached Data Loading for Better Performance

---

## 📂 Dataset

The dataset contains information about OTT content including:

- Title
- Type
- Genre
- Language
- Country
- Release Year
- Runtime
- IMDb Score
- Views
- Watch Hours
- Production Cost
- Revenue
- ROI
- Profit
- Performance Band
- Audience Completion
- Subscribers Gained

---

## 📊 Dashboard Pages

### 📋 Overview
- KPI Cards
- Monthly Content Trend
- Content Type Distribution
- Sample Dataset
- Top Viewed Titles

### 🌐 Genres & Languages
- Top Genres by Views
- Language vs Genre Treemap
- Best & Worst Performing Languages

### 💰 Money
- Production Cost vs Revenue
- ROI Analysis
- Revenue Summary
- Profit Analysis

### 🚨 Quality Alerts
- IMDb Distribution
- IMDb vs Views Analysis
- Loss Making Titles
- Smart Status Messages

---

## 🛠 Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Plotly

---

## 📁 Project Structure

```text
CineStream/
│
├── data/
│   └── CineStream_Catalog.csv
│
├── notebooks/
│   └── m1_explore.ipynb
│
├── outputs/
│   ├── cleaned_cinestream.csv
│   └── m7_report.pdf
│
├── cinestream_app.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/CineStream-Content-Analytics-Dashboard.git
```

Move into the project folder:

```bash
cd CineStream-Content-Analytics-Dashboard
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run cinestream_app.py
```

---

## 📈 Key Insights

The dashboard enables users to:

- Identify high-performing genres and languages.
- Compare production cost with revenue.
- Measure Return on Investment (ROI).
- Track catalog growth over time.
- Analyze the relationship between IMDb ratings and audience engagement.
- Detect financially underperforming titles.

---

## 📸 Dashboard Preview

> Add screenshots of your dashboard here before submitting the project.

---

## 👨‍💻 Author

**Name:** *Sahwa*

**Course:** Bachelor of Computer Applications (BCA)

**Project:** OJT Self Project – CineStream Content Analytics Dashboard

---

