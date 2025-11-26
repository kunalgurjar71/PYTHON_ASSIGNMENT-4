# 🌫️ Air Quality Data Visualizer (Python Project)

### 👨‍🎓 Student Details

* **Name:** Kunal Lohia
* **Course:** BCA (AI & DS) – Semester 1
* **Subject:** Problem Solving with Python
* **Unit:** 4
* **Faculty:** Dr. Satinder Pal Singh
* **Project:** Air Quality Data Visualizer

---

### 📌 Project Overview

This project is a **data cleaning and visualization tool** for Air Pollution data using Python.
It reads pollutant information from a **CSV file (`pollution.csv`)**, cleans the dataset,
and generates meaningful **visual plots and a report**.

✔ Automatic column detection for Date, PM2.5, PM10 & AQI
✔ Data cleaning with missing value handling
✔ Daily AQI trend visualization
✔ Monthly average PM2.5 bar chart
✔ PM2.5 vs PM10 correlation scatter plot
✔ Automatic report and cleaned dataset generation

---

### 🧠 Concepts Used

* Pandas (Data Analysis)
* Matplotlib (Data Visualization)
* File Handling
* Exception Handling
* Data Cleaning & Transformation
* Command-line interaction with users

---

### 🎯 Features Summary

| Feature             | Description                                       |
| ------------------- | ------------------------------------------------- |
| CSV Reading         | Load pollution data into DataFrame                |
| Column Auto-Mapping | Automatically detects relevant air quality fields |
| Date Conversion     | Converts string date to datetime format           |
| Data Cleaning       | Handles NaN values with mean imputation           |
| Visualization       | Line plot, Bar chart, Scatter plot                |
| Reporting           | Creates a simple summary report                   |
| Export              | Saves cleaned CSV & graphs                        |

---

### 🧪 Output Files Generated

| File Name                   | Purpose                             |
| --------------------------- | ----------------------------------- |
| `cleaned_pollution.csv`     | Cleaned dataset                     |
| `aqi_trend.png`             | Line chart of AQI over time         |
| `monthly_pm25.png`          | Bar chart of monthly PM2.5 averages |
| `scatter_pm25_pm10.png`     | Scatter plot comparing pollutants   |
| `report.txt`                | Statistical insights                |
| `system.log` *(if created)* | Runtime logs                        |

---

### 🚀 How to Run the Program

1️⃣ Place your **pollution.csv** file in the same folder
2️⃣ Run the script using:

```
python air_quality_visualizer.py
```

3️⃣ Output files will be saved automatically in the same folder

📌 If column names differ, the program will ask you to enter correct names.

---

### 📂 Folder Structure

```
📁 Air Quality Data Visualizer
│
├── air_quality_visualizer.py    # Main Python script
├── pollution.csv                # Input data file (user provides)
├── cleaned_pollution.csv        # Auto-generated cleaned data
├── report.txt                   # Summary report
├── aqi_trend.png                # AQI trend line plot
├── monthly_pm25.png             # Monthly PM2.5 bar chart
├── scatter_pm25_pm10.png        # Scatter plot
└── README.md                    # Documentation
```

---

### 🎓 Learning Outcomes

From this project, I learned:

* Data visualization using **Matplotlib**
* Data cleaning using **Pandas**
* Automated column mapping for datasets
* Handling user inputs & dynamic processing
* Generating real-world data reports using Python

---

### 🙏 Acknowledgement

Thanks to **Dr. Satinder Pal Singh sir** for guidance and support in Unit-4 Python practicals.

---

📌 *This assignment is created for academic and learning purposes only.*
