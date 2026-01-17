# google-playstore-analytics-dashboard

**📊 Google Play Store Analytics Dashboard**

**Internship Project – Data Analyst**

An interactive analytics dashboard built using Python, Pandas, and Plotly, based on the Google Play Store dataset.
This project extends the training work by implementing advanced analytical tasks, time-based visibility logic, and a unified dashboard.

**🔍 Project Overview**
This project analyzes Google Play Store apps to uncover insights related to:

1.App ratings and reviews
2.Category performance
3.Global installs
4.Revenue vs installs (Free vs Paid)
5.Sentiment impact
6.Growth trends over time

All visualizations are integrated into a single interactive dashboard with time-restricted access, as required by the internship guidelines.

📁 Dataset Used - The project uses the same dataset provided during training (as required):

1.Play Store Data.csv
2.User Reviews.csv
❗ No external or unrelated datasets were used.

**🛠️ Tools & Technologies**

*Python
*Pandas
*Plotly (Express & Graph Objects)
*HTML / CSS
*Jupyter Notebook
*GitHub Pages (Hosting)

**📊 Dashboard Tasks Implemented**
**Task 1 – Ratings vs Reviews (Grouped Bar Chart)**

**Filters:**
  *Rating ≥ 4.0
  *App size ≥ 10 MB
  *Last updated in January
  *Top 10 categories by installs
  *Time visibility: 3 PM – 5 PM IST

**Task 2 – Free vs Paid Apps (Dual-Axis Chart)**
Compares average installs vs revenue

**Filters:**
  *Android version > 4.0
  *Size > 15 MB
  *Content rating = Everyone
  *App name ≤ 30 characters
  *Installs ≥ 10,000
  *Revenue ≥ $10,000
  *Time visibility: 1 PM – 2 PM IST

**Task 3 – Global Installs (Choropleth Map)
**
  *Top 5 categories by installs
  *Excludes categories starting with A, C, G, S
  *Highlights installs > 1 million
  *Time visibility: 6 PM – 8 PM IST

**Task 4 – Cumulative Installs Over Time (Stacked Area Chart)**

**Filters:**
  *Rating ≥ 4.2
  *No numbers in app name
  *Categories starting with T or P
  *Reviews > 1,000
  *Size between 20–80 MB

**Category translations:**
  *Travel & Local → French
  *Productivity → Spanish
  *Photography → Japanese
  *Highlights >25% MoM growth
  *Time visibility: 4 PM – 6 PM IST

**Task 5 – Size vs Rating (Bubble Chart)
**
Bubble size = installs

**Filters:**
  *Rating > 3.5
  *Reviews > 500
  *Installs > 50,000
  *Sentiment subjectivity > 0.5
  *App name does not contain “S”

**Category translations:**
  Beauty → Hindi
  Business → Tamil
  Dating → German

*GAME category highlighted in pink
*Time visibility: 5 PM – 7 PM IST

**Task 6 – Installs Trend Over Time (Line Chart)
**
Categories starting with E, C, or B

**App name:**
  Does not start with X, Y, Z
  Does not contain “S”
  Reviews > 500
  Highlights >20% MoM growth
  Category translations applied
  Time visibility: 6 PM – 9 PM IST

🖥️ Dashboard Preview

Task 1 – Ratings vs Reviews
![Task 1]
([./Screenshot%202026-01-17%20231620.png](https://github.com/Paru-06/google-playstore-analytics-dashboard/blob/main/Screenshot%202026-01-17%20231620.png))

Task 2 – Category Analysis



Task 3 – Global Installs



Task 4 – Cumulative Installs



Task 5 – Bubble Chart



Task 6 – Time Series Trend




---

🌐 Live Project

Dashboard URL (GitHub Pages):
👉 (https://paru-06.github.io/google-playstore-analytics-dashboard/)

📂 Repository Structure

google-playstore-analytics-dashboard/
│
├── dashboard.html
├── task1.html
├── task2.html
├── task3.html
├── task4.html
├── task5.html
├── task6.html
├── Play Store Data.csv
├── User Reviews.csv
├── screenshots/
│   ├── task1_ratings_vs_reviews.png
│   ├── task2_category_analysis.png
│   ├── task3_choropleth.png
│   ├── task4_area_chart.png
│   ├── task5_bubble_chart.png
│   └── task6_time_series.png
└── README.md

**📝 Notes**

1.All internship tasks were implemented on one unified dataset
2.Time-based visibility is handled programmatically
3.Project is fully reproducible and interactive
4.Follows all NullClass internship submission rules

**👤 Author**

Parkavi K
Data Analyst Intern
