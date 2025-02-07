# 🏎️ **Cablytics: Data Engineering and Visualization for Cab Service Operations**

Cablytics is an end-to-end data engineering and visualization project designed to provide actionable insights into cab service performance. By leveraging a seamless data pipeline, we integrated, transformed, and visualized key metrics, allowing for optimized decision-making and enhanced business intelligence.

## 📊 **Dashboard Link**

[Access the Cablytics Dashboard on Looker Studio](https://lookerstudio.google.com/reporting/64ab5f11-6793-4451-93fc-b4927b9ef2e5)

---

## 📂 **Repository Contents**
- **`CabLytics.ipynb`**: Jupyter notebook containing the core data analysis and modeling for the cab service data.
- **`DataLoader.py`**: Python script for loading raw data and preprocessing it for further analysis.
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

### 1. **Process Flow**
This diagram illustrates the overall **process flow** of the data pipeline. The steps include:

1. **Raw Data in Cloud Storage**: Data is initially stored in cloud storage (e.g., Google Cloud Storage) as raw files.
2. **Compute Engine with Mage**: Data is ingested, cleaned, and transformed using **Google Cloud Compute Engine** and **Mage** (an ETL tool).
3. **BigQuery for Analytics**: Transformed data is loaded into **Google BigQuery** for optimized storage and querying.
4. **Looker Studio for Visualization**: The processed data is then visualized through **Looker Studio**, providing real-time insights and interactive dashboards.

![Process Flow](https://github.com/ahtisham73/CabLytics/blob/d9ec72e8cdbef0d474682828eb6191d83dfe5054/Process%20flow%20Diagram.png)

*Process Flow Overview*

---

### 2. **ETL Data Pipeline Design**


The ETL data pipeline, designed using **Mage** on **Google Cloud VM**, handles data ingestion, transformation, and loading into **Google BigQuery**. Below is the **data pipeline workflow** diagram:

![ETL Pipeline Diagram](https://github.com/ahtisham73/CabLytics/blob/a0fa780adca137a1baaf6885ee7c6d65c2b578db/Data_PipeLine.png)

*Data Pipeline Workflow*

---


### 3. **Star Schema Data Model**

The **Star Schema** is used to model the data. It helps in organizing fact and dimension tables efficiently. The Star Schema is designed for optimized query performance:

![Star Schema](https://github.com/ahtisham73/CabLytics/blob/d9ec72e8cdbef0d474682828eb6191d83dfe5054/Star%20Schema.png)

*Star Schema Data Model*

---

### 4. **BigQuery Data Modeling**

- **Fact and Dimension Tables**: The data is modeled in a **Star Schema**, where the fact tables store business metrics (e.g., revenue, trips), and the dimension tables store descriptive information (e.g., cab IDs, driver IDs, location data).
- **Optimized Queries**: The fact and dimension tables are designed to ensure fast, efficient querying, supporting scalable business intelligence.

---

### 5. **Looker Studio Dashboard**

The **Looker Studio Dashboard** provides an interactive visualization of the cab service's key performance metrics. It shows various trends and insights:

- **Cab Service Trends**: Performance changes over time.
- **KPIs**: Metrics like total revenue, average trips per day, driver performance, etc.
- **Performance Metrics**: Visualizations for key indicators like customer satisfaction, trip duration, and revenue per trip.

---

## 📈 **Dashboard Features**

The interactive dashboard offers:
- **Ride-sharing data**: Trends, revenue, trip counts, and more.
- **Geospatial Insights**: Maps displaying service coverage and driver performance across locations.
- **Key Performance Indicators (KPIs)**: Metrics for tracking performance, revenue, and efficiency.
- **Time-Based Analysis**: Breakdown of data by day, hour, and time to analyze peak times and trends.

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

---

🚀 Contributions are welcome! 
Submit a PR or open an issue to collaborate. Let’s build smarter

---

## 📨 Contact

You can reach me via email at [ahtishamsudheer@gmail.com](mailto:ahtishamsudheer@gmail.com)

---

🌟 **Give this repo a star if you found it useful!** ⭐


