# ✈️ NYC Flights Data Analysis

## 📌 Project Overview

This project focuses on cleaning and exploring the **NYC Flights dataset** to better understand flight operations and delay patterns.

The main goal is to perform a structured **Exploratory Data Analysis (EDA)** and extract meaningful insights about airline performance, delays, and flight distribution.

---

## 🎯 Objectives

* Understand the dataset structure and features
* Clean the data (handle missing values and duplicates)
* Analyze departure and arrival delays
* Explore patterns across airlines, airports, and destinations
* Identify key factors affecting flight delays

---

## 📂 Dataset

The dataset used in this project is the **NYC Flights dataset**, which contains information about flights departing from New York City, including:

* Flight details (carrier, flight number)
* Departure and arrival times
* Delay information
* Origin and destination airports
* Time-related features (year, month, day, hour)

> ⚠️ Note: The dataset is not included in this repository. Please add it manually in a `data/` folder:

```
data/nycflights.csv
```

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Project Structure

```
NYC-Flights-Analysis/
│
├── data/
│   └── nycflights.csv
│
├── notebooks/
│   └── nyc_flights_analysis.ipynb
│
├── README.md
└── requirements.txt (optional)
```

---

## 🧹 Data Cleaning Steps

* Removed duplicate records
* Identified and handled missing values
* Checked data types and converted where necessary
* Ensured consistency across key columns

---

## 📊 Exploratory Data Analysis

The analysis includes:

* Distribution of airlines and routes
* Delay analysis (departure & arrival)
* Comparison of average delays across carriers
* Relationship between departure delay and arrival delay
* Grouped analysis by airline, airport, and time

---

## 📈 Key Insights

* ✈️ Departure delays have a strong impact on arrival delays
* 🏢 Some airlines consistently experience higher delays than others
* 📍 Flight activity is concentrated among a few major carriers and routes
* ⚠️ Missing values are mainly present in delay-related columns

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Jalalazezibrahem/nyc-flights-analysis.git
```

2. Navigate to the project folder:

```bash
cd nyc-flights-analysis
```

3. Install dependencies (optional):

```bash
pip install -r requirements.txt
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 💡 Future Improvements

* Build a predictive model for flight delays
* Perform advanced feature engineering
* Add interactive visualizations (Plotly / Dash)
* Deploy the project as a web app

---

## 👨‍💻 Author

**Jalal Ibrahim**
AI Engineering Student

---

## ⭐ Support

If you found this project useful, feel free to ⭐ the repository!
