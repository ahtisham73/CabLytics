# 🏎️ **Cablytics: Data Engineering and Visualization for Cab Service Operations**

Cablytics is an end-to-end data engineering and visualization project designed to provide actionable insights into cab service performance. By leveraging a seamless data pipeline, we integrated, transformed, and visualized key metrics, allowing for optimized decision-making and enhanced business intelligence.

## 📊 **Dashboard Link**

[Access the Cablytics Dashboard on Looker Studio](https://lookerstudio.google.com/reporting/64ab5f11-6793-4451-93fc-b4927b9ef2e5)

---

## 📂 **Repository Contents**
- **`CabLytics.ipynb`**: Jupyter notebook containing the core data analysis and modeling for the cab service data.
-  **`DataLoader.py`**: Python script for loading raw data and preprocessing it for further analysis.
- **`DataExporter.py`**: Python script responsible for exporting the transformed data to the required format.
- **`Transformer.py`**: Python script that handles data transformation, including cleaning and feature engineering.
- **`Query2.md`**: Markdown file containing SQL queries used for data extraction and transformation.
- **`data.csv`**: Raw data file used for analysis and modeling in the project.
- **`README.md`**: Project documentation and instructions for running the project.
- **`LICENSE`**: The license file for the project.
---

## 🧑‍💻 **Project Overview**
Cablytics is a comprehensive solution that tracks cab service performance through a robust ETL pipeline and a dynamic dashboard. The project comprises three main components:

1. **Data Pipeline**: The ETL process pulls raw data, cleanses it, and loads it into BigQuery.
2. **BigQuery Data Modeling**: Transformed data is modeled into fact and dimension tables for efficient querying.
3. **Dashboard Visualization**: The data is visualized in an interactive dashboard that provides real-time insights into trends, key performance indicators (KPIs), and performance metrics.

---

## 🔧 **Implemented Steps**

### 1. **ETL Data Pipeline Design**
- **Tool**: Mage, a powerful tool for creating, automating, and managing ETL workflows.
- **Environment**: Google Cloud VM for cloud-based processing and scalability.
- **Process**: 
  - Data is ingested from various sources (e.g., transaction logs, trip details).
  - Cleaned and transformed using Mage’s user-friendly interface.
  - Loaded into Google BigQuery for fast, optimized queries.

### 2. **BigQuery Data Modeling**
- **Fact and Dimension Tables**: I designed data models to store structured data in a way that supports complex queries. The fact tables store metrics (e.g., total revenue, number of trips), while the dimension tables store descriptive data (e.g., cab IDs, driver IDs, location data).
- **Optimized Queries**: The tables were designed to ensure fast and efficient querying, supporting scalable business intelligence.

### 3. **Looker Studio Dashboard**
- **Looker Studio**: Created an interactive dashboard to visualize key metrics and insights.
- **Visualizations**:
  - **Cab Service Trends**: Shows changes in performance over time.
  - **KPIs**: Includes metrics like total revenue, average trips per day, and driver performance.
  - **Performance Metrics**: Visualized key performance indicators like customer satisfaction, trip duration, and revenue per trip.
- **Interactivity**: Users can filter the data by different time periods, locations, and other parameters, allowing for detailed drilldowns and customized views.

---

## 📈 **Dashboard Features**

The dashboard provides a user-friendly interface that displays:
- **Ride-sharing data**: Visualizes trends, revenue, trip counts, etc.
- **Geospatial Insights**: Maps that show the service coverage and driver performance across locations.
- **Key Performance Indicators (KPIs)**: Key metrics for performance tracking, revenue generation, and trip efficiency.
- **Time-Based Analysis**: Breakdown of data by date, hour, and day, allowing users to identify peak times and patterns.

---

## 📋 **How to Run the ETL Pipeline**

To run the ETL pipeline and replicate the data processing workflow:

### Prerequisites:
1. **Google Cloud VM**: You’ll need access to a Google Cloud account and a virtual machine with sufficient resources.
2. **Mage Installation**: Mage should be installed and configured. You can install Mage from [Mage's Official Site](https://www.mage.ai/).
3. **BigQuery Access**: Set up Google BigQuery for data storage and analytics.

## 🐙 **Clone the repository:**
  ```bash
       git clone https://github.com/your_repo/Cablytics.git
  ```
 
## 🔧 **Set up Mage and Google Cloud VM:**
1. Set up a VM on Google Cloud.
2. Install Mage on the VM.
3. Connect Mage to Google Cloud VM and BigQuery.

 ## 🚀 **Run the ETL Pipeline:**
1. Use Mage to create a pipeline that ingests raw data, transforms it, and loads it into BigQuery.

 ## 📊 **Query the Data:**
1. Use SQL queries to access the fact and dimension tables stored in BigQuery.
2. Access the Looker Studio dashboard for visualizations.

---

## 📅 **Conclusion**
The Cablytics project provides a comprehensive solution for cab service data analysis. With the ETL pipeline, BigQuery data modeling, and interactive Looker Studio dashboard, the project enables efficient and actionable insights into performance metrics, trends, and operational efficiency.

Feel free to access the Cablytics Dashboard on Looker Studio and explore the insights.

---

## 📜 **References**
- Mage Documentation
- Google Cloud BigQuery
- Looker Studio

---

## 📝 **Future Work**
- **Integration with Other Data Sources**: Integrate additional data streams such as customer feedback and real-time traffic data.
- **Advanced Analytics**: Implement predictive analytics to forecast demand and optimize fleet management.
- **Real-Time Dashboard Updates**: Implement streaming data for real-time dashboard refreshes.

