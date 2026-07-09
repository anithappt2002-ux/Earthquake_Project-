# 🌍 Earthquake_Project – Global Seismic Trends: Data-Driven Earthquake Insights

## 📌 Project Overview

The **Earthquake_Project** is a data analytics project that collects, processes, stores, and analyzes global earthquake data. The project uses the **USGS Earthquake API** to retrieve earthquake information and provides meaningful insights through SQL analysis and an interactive Streamlit dashboard.

---

# 🎯 Problem Statement

Earthquakes occur worldwide every day, generating large volumes of seismic data. Analyzing this data helps identify earthquake patterns, high-risk regions, magnitude trends, and depth distributions, supporting disaster preparedness and research.

---

# 🎯 Objectives

* Retrieve earthquake data from the USGS API.
* Clean and preprocess raw earthquake data.
* Store processed data in a MySQL database.
* Perform SQL-based analytical queries.
* Develop an interactive Streamlit dashboard.
* Generate insights from global earthquake trends.

---

# 🛠️ Technologies Used

* Python
* Pandas
* Requests
* MySQL
* SQLAlchemy
* SQL
* Streamlit
* Matplotlib
* Seaborn

---

# 📂 Dataset

**Source:** USGS Earthquake API

The dataset contains earthquake information such as:

* Event ID
* Date & Time
* Latitude
* Longitude
* Magnitude
* Magnitude Type
* Depth (km)
* Place
* Status
* Tsunami Indicator
* Significance
* Reporting Network
* Source Information

---

# 🔄 Project Workflow

1. Data Collection

   * Retrieve earthquake data using the USGS API.

2. Data Preprocessing

   * Handle missing values.
   * Remove duplicate records.
   * Convert data types.
   * Extract Year, Month, Day, and Day of Week.
   * Create Country and Depth Category columns.

3. Database Storage

   * Store cleaned data in MySQL using SQLAlchemy.

4. SQL Analysis

   * Perform analytical queries on earthquake data.

5. Dashboard Development

   * Build an interactive dashboard using Streamlit.

---

# 📊 Dashboard Features

* Total Earthquakes
* Magnitude Distribution
* Earthquakes by Country
* Monthly Earthquake Trends
* Depth Category Analysis
* Strongest Earthquakes
* Tsunami Analysis
* SQL Query Results

---

# 📈 Key Insights

* Most earthquakes occur at shallow depths.
* Earthquake frequency varies across different years and regions.
* High-magnitude earthquakes are less common than moderate events.
* Certain countries experience significantly more seismic activity.
* Interactive dashboards make it easier to explore seismic trends and patterns.

---

# 📁 Project Structure

```text
Earthquake_Project/
│
├── data/
├── notebooks/
├── app.py
├── earthquake_api.py
├── preprocessing.py
├── database.py
├── sql_queries.py
├── requirements.txt
├── README.md
└── screenshots/
```

---

# 🚀 How to Run the Project

1. Clone the repository.
2. Install the required Python libraries.
3. Configure the MySQL database connection.
4. Run the data extraction and preprocessing scripts.
5. Launch the Streamlit dashboard.

---

# 📌 Future Enhancements

* Real-time earthquake monitoring.
* Interactive map visualizations.
* Machine learning for earthquake trend prediction.
* Automated daily data updates.
* Cloud deployment.

---

# 👩‍💻 Developed By

**Anitha Karthik**

Data Analytics Project using Python, MySQL, SQL, and Streamlit.
