🚗 Car Crash Hotspot Analysis
📌 Project Overview

This project analyzes car crash data to uncover spatial and temporal hotspots. The aim is to identify where and when crashes are most likely to occur, and to build a predictive model that flags potential hotspot locations.

We combine data wrangling, visualization, and machine learning to tell a complete story: from cleaning raw data to actionable insights.

🔍 Objectives

Explore crash trends across location, time, and conditions.

Identify high-risk crash hotspots using spatial binning.

Analyze time-of-day and day-of-week patterns.

Build and evaluate machine learning models for hotspot prediction.

📂 Project Structure
Car_Crashes_Project/
│
├── Car_Crashes_Project.ipynb   # Main Jupyter notebook
├── data/                       # Raw or cleaned crash data
├── figures/                    # Exported charts and visualizations
├── README.md                   # Project documentation
└── requirements.txt             # Python dependencies

⚙️ Tools & Libraries

Python: pandas, numpy

Visualization: matplotlib, seaborn

ML Models: scikit-learn, XGBoost (optional LightGBM)

Other: SMOTE (imbalanced-learn) for resampling

📊 Key Insights

🚦 Spatial Hotspots: High crash density in specific lat/lon grid cells.

🕑 Temporal Patterns: Peaks during morning and evening rush hours.

📅 Day-of-Week Trends: Higher crash frequencies on weekends vs weekdays.

🤖 Modeling: Predictive classifiers (Random Forest, XGBoost) tested for hotspot prediction.
powerpoint presentation : https://www.canva.com/design/DAGzGgtJWJo/oUAPoVh43P1ehpBK6FAUdQ/edit?ui=e30
