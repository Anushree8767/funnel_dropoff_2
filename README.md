# 📊 Funnel Drop-off Analysis using SQL (DuckDB) & Python

## 📌 Project Overview

This project analyzes event-level user data from a signup/checkout funnel to measure user progression across each stage. The analysis calculates unique users at every stage, stage-to-stage conversion rates, and identifies the largest drop-off point to highlight where users abandon the funnel.

---

## 🎯 Project Objective

- Count unique users at each funnel stage.
- Calculate stage-to-stage conversion rates.
- Identify the biggest user drop-off in the funnel.
- Visualize funnel performance using a bar chart.
- Provide actionable business recommendations.

---

## 🛠️ Tools & Technologies

- SQL (DuckDB)
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains event-level records with the following columns:

- **user_id** – Unique identifier for each user.
- **step** – Funnel stage reached by the user.
- **timestamp** – Time when the event occurred.

---

## 📈 Analysis Performed

- Loaded the dataset into DuckDB.
- Counted unique users at each funnel stage using SQL.
- Calculated stage-to-stage conversion rates.
- Identified the stage with the highest user drop-off.
- Visualized funnel stages using a bar chart.
- Added business insights and recommendations.

---

## 📊 Key Metrics

- Unique Users by Stage
- Conversion Rate (%)
- Users Lost Between Stages
- Biggest Funnel Drop-off

---

## 📷 Project Output

### 📒 Jupyter Notebook
-<a href="(https://github.com/Anushree8767/funnel_dropoff_2/blob/main/funnel_dropoff_2.ipynb)">funnel dropoff </a>

### 📊 Visualization
<img width="1148" height="651" alt="Screenshot 2026-08-01 142854" src="https://github.com/user-attachments/assets/717d1565-9380-4e06-81b1-acf9b28ae19f" />


---

## 💡 Business Insight

The analysis identifies the stage with the largest user drop-off, helping product teams understand where users abandon the funnel. Improving this stage can increase overall conversion and enhance the user experience.

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Funnel-Dropoff-Analysis.git
```

2. Open the project folder.

3. Install the required libraries.

```bash
pip install duckdb pandas matplotlib
```

4. Place the dataset in the project folder.

5. Open the Jupyter Notebook and run all cells.

---

⭐ If you found this project helpful, consider giving it a star.
