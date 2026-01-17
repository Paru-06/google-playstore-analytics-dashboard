📊 Google Play Store Analytics Dashboard

An **interactive analytics dashboard** built using the **Google Play Store datasets**, developed as part of my **Data Analytics Internship project**.  
All tasks are implemented by **building on the original training project**, strictly following internship instructions.

✔ Same dataset as training  
✔ No unrelated datasets  
✔ No new projects  

---

📁 Datasets Used

This project is built using the **official Google Play Store datasets**:

• **Play Store Data.csv**  
  → App details such as category, rating, installs, size, reviews, last updated, etc.

• **User Reviews.csv**  
  → User sentiment data including subjectivity and polarity scores


---

🌟 Project Overview

The dashboard provides insights into:

📌 App performance & ratings  
📌 Category-wise install trends  
📌 Free vs Paid app revenue comparison  
📌 Global installs visualization  
📌 Sentiment-based app analysis  
📌 Time-based growth highlighting  

All analyses are combined into a **single live dashboard**, hosted using **GitHub Pages**.

---

🧩 Implemented Tasks

### 🔹 Task 1 – Ratings vs Reviews
Grouped bar chart comparing **average rating** and **total reviews** for the top 10 categories by installs.

**Filters applied:**
• Rating ≥ 4.0  
• Size ≥ 10 MB  
• Last updated in January  

⏰ Visible only between **3 PM – 5 PM IST**

📸 Screenshot:  
### 🟢 Task 1 – Ratings vs Reviews
![Task 1](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231620.png)


---

### 🔹 Task 2 – Free vs Paid Category Analysis
Dual-axis chart comparing **average installs** and **average revenue** for Free vs Paid apps.

**Filters applied:**
• Android version > 4.0  
• Size > 15 MB  
• Content rating = Everyone  
• App name ≤ 30 characters  
• Installs ≥ 10,000  
• Revenue ≥ $10,000  

⏰ Visible only between **1 PM – 2 PM IST**

📸 Screenshot:  
### 🟢 Task 2 – Category Analysis
![Task 2](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231653.png)

---

### 🔹 Task 3 – Global Installs Choropleth Map 🌍
Interactive map showing **global installs by app category**.

**Conditions:**
• Top 5 categories only  
• Categories NOT starting with A, C, G, or S  
• Highlight installs > 1 million  

⏰ Visible only between **6 PM – 8 PM IST**

📸 Screenshot:  
### 🟢 Task 3 – Global Installs (Choropleth Map)
![Task 3](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231730.png)


---

### 🔹 Task 4 – Cumulative Installs Over Time 📈
Stacked area chart showing **cumulative installs by category over time**.

**Special features:**
• App filters based on rating, reviews, size  
• Category translations in legend  
• Months with **>25% MoM growth highlighted using increased color intensity**

⏰ Visible only between **4 PM – 6 PM IST**

📸 Screenshot:  
### 🟢 Task 4 – Cumulative Installs (Stacked Area Chart)
![Task 4](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231808.png)

---

### 🔹 Task 5 – Bubble Chart Analysis 🔵
Bubble chart showing the relationship between **app size, rating, and installs**.

**Additional conditions:**
• Rating > 3.5  
• Reviews > 500  
• App name does NOT contain “S”  
• Sentiment subjectivity > 0.5  
• Installs > 50,000  
• GAME category highlighted in **pink**

**Category Translations:**
• Beauty → Hindi  
• Business → Tamil  
• Dating → German  

⏰ Visible only between **5 PM – 7 PM IST**

📸 Screenshot:  
### 🟢 Task 5 – Bubble Chart Analysis
![Task 5](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231836.png)


---

### 🔹 Task 6 – Install Trends Over Time ⏱
Time-series line chart showing **total installs trend over time by category**.

**Highlights:**
• Categories starting with E, C, or B  
• App names not starting with X, Y, Z  
• Reviews > 500  
• >20% MoM growth highlighted using shaded regions  
• Category translations applied

⏰ Visible only between **6 PM – 9 PM IST**

📸 Screenshot:  
### 🟢 Task 6 – Time Series Trend
![Task 6](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231853.png)


---

🧭 Dashboard View

### ✅ Dashboard During Active Time
![Dashboard Active](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20231917.png)

### ⛔ Dashboard During Restricted Time
![Dashboard Restricted](https://raw.githubusercontent.com/Paru-06/google-playstore-analytics-dashboard/main/Screenshot%202026-01-17%20232041.png)
---

⏰ Time-Based Visibility Logic

Each task is protected using **strict IST time gates**.

Outside the allowed time window:
✔ Graph is hidden  
✔ “Task Unavailable” message is shown  
✔ Dashboard layout remains consistent  

This ensures **full compliance with internship requirements**.

---

🚀 Live Project Links

🌐 **Live Dashboard (GitHub Pages):**  
https://paru-06.github.io/google-playstore-analytics-dashboard/

📂 **GitHub Repository:**  
https://github.com/Paru-06/google-playstore-analytics-dashboard

---

🛠 Tools & Technologies

• Python  
• Pandas  
• Plotly (Graph Objects & Express)  
• Jupyter Notebook  
• HTML & CSS  
• GitHub Pages  

---

✨ Final Note

This project demonstrates my ability to:
✔ Clean and transform real-world datasets  
✔ Apply complex filtering logic  
✔ Build interactive, time-controlled dashboards  
✔ Present insights in a clear and professional manner  

👩‍💻 **Parkavi K**  
📊 *Data Analytics Intern*  
🌟 *This internship experience was insightful, challenging, and highly valuable for my learning journey.*
