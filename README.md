# 🏨 Hotel Booking Data Analysis

<p align="center">
  <strong>Hotel Booking Data Analysis using Python, Pandas, NumPy & Matplotlib</strong>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-objectives">Objectives</a> •
  <a href="#-technologies">Technologies</a> •
  <a href="#-dataset">Dataset</a> •
  <a href="#-analysis">Analysis</a> •
  <a href="#-visualizations">Visualizations</a> •
  <a href="#-project-structure">Structure</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-results">Results</a>
</p>

---

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on hotel booking data to understand booking behavior, cancellation patterns, hotel performance, customer preferences, market segments, lead time, and Average Daily Rate (ADR).

The analysis uses **Python, Pandas, NumPy, and Matplotlib** to transform raw booking data into meaningful insights through statistical analysis and visualizations.

---

## 🎯 Objectives

* Analyze total hotel bookings
* Calculate the overall cancellation rate
* Compare City Hotel and Resort Hotel bookings
* Analyze monthly booking trends
* Study customer types
* Analyze meal preferences
* Examine market segments
* Compare Average Daily Rate (ADR)
* Analyze lead-time patterns
* Identify cancellation patterns
* Understand relationships between lead time and ADR

---

## 🛠️ Technologies

| Technology    | Purpose                        |
| ------------- | ------------------------------ |
| 🐍 Python     | Data analysis                  |
| 🐼 Pandas     | Data manipulation and analysis |
| 🔢 NumPy      | Numerical calculations         |
| 📊 Matplotlib | Data visualization             |
| 🔍 EDA        | Exploratory Data Analysis      |
| 📈 Statistics | Business insights              |

---

## 📂 Dataset

The dataset is stored in:

```text
data/hotel_bookings.csv
```

### Dataset Columns

| Column           | Description                                |
| ---------------- | ------------------------------------------ |
| `Booking_ID`     | Unique booking identifier                  |
| `Hotel`          | Hotel type                                 |
| `Lead_Time`      | Number of days between booking and arrival |
| `Arrival_Month`  | Arrival month                              |
| `Customer_Type`  | Type of customer                           |
| `Meal`           | Meal plan selected                         |
| `Market_Segment` | Booking market segment                     |
| `ADR`            | Average Daily Rate                         |
| `Booking_Status` | Cancellation status                        |

---

## 🔎 Analysis

### 🏨 Hotel Analysis

The project compares:

* City Hotel
* Resort Hotel

It analyzes booking volume and average ADR for each hotel type.

### ❌ Cancellation Analysis

The project calculates:

* Total bookings
* Canceled bookings
* Non-canceled bookings
* Overall cancellation rate
* Cancellation rate by hotel type

### 📅 Monthly Booking Analysis

Booking volumes are analyzed across:

* January
* February
* March
* April

This helps identify monthly booking patterns within the dataset.

### 👥 Customer Analysis

The project analyzes bookings by customer type, including:

* Transient
* Contract
* Group

### 🍽️ Meal Analysis

Meal preferences are analyzed to identify the most frequently selected meal plan.

### 🌐 Market Segment Analysis

The project examines booking sources such as:

* Online TA
* Offline TA
* Corporate
* Direct

### 💰 ADR Analysis

The project calculates:

* Average ADR
* Median ADR
* Highest ADR
* Lowest ADR
* ADR by hotel type
* ADR variability

### ⏱️ Lead Time Analysis

Lead time is analyzed to understand how far in advance customers make hotel bookings.

---

## 📊 Visualizations

The project generates multiple visualizations:

* Hotel Type Distribution
* Booking Status Distribution
* Monthly Booking Trends
* Cancellation Rate by Hotel Type
* Average Daily Rate by Hotel Type
* Bookings by Customer Type
* Bookings by Market Segment
* Lead Time Distribution
* Meal Preference Distribution
* Lead Time vs ADR

---

## 📈 Key Metrics

The analysis calculates:

```text
Total Bookings
Canceled Bookings
Not Canceled Bookings
Cancellation Rate
Average ADR
Median ADR
Highest ADR
Lowest ADR
Average Lead Time
ADR Range
ADR Standard Deviation
Lead Time Standard Deviation
```

---

## 📁 Project Structure

```text
Hotel-Booking-Data-Analysis/
│
├── data/
│   └── hotel_bookings.csv
│
├── hotel_booking_analysis.py
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/shejal24-rgb/Hotel-Booking-Data-Analysis.git
```

Navigate to the project:

```bash
cd Hotel-Booking-Data-Analysis
```

Install required libraries:

```bash
pip install pandas numpy matplotlib
```

---

## ▶️ Run the Project

Run the Python analysis file:

```bash
python hotel_booking_analysis.py
```

The program will display statistical summaries and generate multiple Matplotlib visualizations.

---

## 💡 Business Questions

This project helps answer questions such as:

* Which hotel type receives more bookings?
* What percentage of bookings are canceled?
* Which hotel type has the higher cancellation rate?
* Which month has the highest number of bookings?
* Which customer type is most common?
* Which market segment generates the most bookings?
* Which meal plan is most preferred?
* Which hotel type has the higher ADR?
* How are lead times distributed?
* Is there a relationship between lead time and ADR?

---

## 📚 Learning Outcomes

Through this project, you will practice:

* Data loading with Pandas
* Data cleaning and validation
* Missing-value analysis
* Duplicate detection
* Descriptive statistics
* GroupBy analysis
* Sorting and aggregation
* Business KPI calculation
* Exploratory Data Analysis
* Data visualization
* Statistical interpretation
* GitHub project organization

---

## 🚀 Future Enhancements

Possible improvements include:

* Add Seaborn visualizations
* Create an interactive Power BI dashboard
* Add monthly revenue analysis
* Add customer segmentation
* Perform correlation analysis
* Add advanced cancellation prediction
* Build a machine learning model
* Add interactive Plotly dashboards

---

## 👨‍💻 Author

**Shejal Dhakate**

📌 Data Analysis Portfolio Project 

🔗 GitHub: https://github.com/shejal24-rgb

🔗 LinkedIn: https://linkedin.com/in/shejaldhakate

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Part of a Daily Data Analysis Project Series using Python, Pandas, NumPy & Matplotlib.**
