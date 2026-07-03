# 🎬 CineStream Content Analytics Dashboard

## Project Overview
This project is an interactive Streamlit dashboard developed for CineStream, a fictional OTT streaming platform. It provides business insights by analyzing the content catalog using interactive filters, KPIs, charts, and performance metrics.

## Features
- Interactive dashboard using Streamlit
- Sidebar filters
- KPI cards
- Genre and Language analysis
- Revenue and ROI analysis
- Quality Alerts
- CSV download option
- Interactive charts using Matplotlib and Plotly

## Dataset
The dataset contains information about Movies, Series, Documentaries, and Stand-up specials, including:
- Genre
- Language
- Country
- IMDb Score
- Views
- Watch Hours
- Revenue
- Production Cost
- ROI
- Profit
- Performance Band

## Technologies Used
- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Plotly

## Project Structure

```
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

## Run the Project

```bash
pip install -r requirements.txt
streamlit run cinestream_app.py
```

## Author

Name: Your Name

Course: BCA Semester 4 OJT Project