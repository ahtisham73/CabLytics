# 🏎️ **Cablytics: Data Engineering & Visualization for Cab Service Operations**

Cablytics is an end-to-end data engineering and visualization project that turns raw cab service data into actionable insights! 🚗📊 Perfect for learning ETL pipelines, BigQuery modeling, and dashboard creation—ideal for your university exams. This project integrates data pipelines, transforms it using Google Cloud tools, and visualizes performance metrics in an interactive dashboard.

## 📊 **Dashboard Link**

[Explore the Cablytics Dashboard on Looker Studio](https://lookerstudio.google.com/reporting/64ab5f11-6793-4451-93fc-b4927b9ef2e5)

---

## 📂 **Project Directory Structure**

```
Cablytics/
├── 📜 README.md                  # Project Overview and Instructions
├── 📂 src/                       # Source Code and Scripts
│   ├── 📜 CabLytics.ipynb        # Jupyter Notebook for Data Analysis
│   ├── 📜 DataExporter.py        # Script for Exporting Transformed Data
│   ├── 📜 DataLoader.py          # Script for Loading and Preprocessing Data
│   ├── 📜 Transformer.py         # Script for Data Transformation
├── 📂 docs/                      # Documentation and Diagrams
│   ├── 📜 Query2.md              # SQL Queries for Data Extraction
│   ├── 📜 Process_flow_Diagram.png  # Process Flow Diagram
│   ├── 📜 Data_PipeLine.png      # ETL Pipeline Workflow Diagram
│   ├── 📜 Star_Schema.png        # Star Schema Data Model
├── 📂 data/                      # Raw and Processed Data
│   ├── 📜 data.csv               # Raw Data File
├── 📜 LICENSE                    # License File
└── 📜 .gitignore                 # Git Ignore File
```

---

## 🧑‍💻 **Project Overview**

Cablytics tracks cab service performance with a robust **ETL pipeline**, **BigQuery data modeling**, and an interactive **Looker Studio dashboard**. It’s a great way to master data engineering concepts for your coursework! The project breaks down into:

1. **Data Pipeline**: Extracts, transforms, and loads (ETL) raw data into BigQuery.
2. **BigQuery Data Modeling**: Organizes data into fact and dimension tables for efficient querying.
3. **Dashboard Visualization**: Displays real-time insights like trends and KPIs.

### 🎯 Example Scenario
Imagine a cab company with messy data on trips and revenue. Cablytics pulls this data, cleans it (e.g., fixing missing values), loads it into BigQuery, and creates a dashboard showing peak trip times and driver performance. The manager uses this to schedule more cabs during rush hours! 🚕

---

## 🔧 **Implemented Steps**

### 1. **Process Flow**
This diagram shows the data pipeline’s journey:

- **Raw Data in Cloud Storage**: Starts with data in Google Cloud Storage.
- **Compute Engine with Mage**: Cleans and transforms data using Google Cloud Compute Engine and Mage.
- **BigQuery for Analytics**: Loads data into BigQuery for querying.
- **Looker Studio for Visualization**: Visualizes insights in an interactive dashboard.

![Process Flow](docs/Process_flow_Diagram.png)  
**_Figure 1: Process Flow Overview_**

---

### 2. **ETL Data Pipeline Design**
The ETL pipeline, built with **Mage** on a **Google Cloud VM**, handles data ingestion, transformation, and loading into **BigQuery**. Check the workflow:

![ETL Pipeline Diagram](docs/Data_PipeLine.png)  
**_Figure 2: ETL Pipeline Workflow_**

---

### 3. **Star Schema Data Model**
The **Star Schema** organizes data for fast queries:

- **Fact Tables**: Store metrics like revenue and trip counts.
- **Dimension Tables**: Hold details like cab IDs and locations.

![Star Schema](docs/Star_Schema.png)  
**_Figure 3: Star Schema Data Model_**

---

### 4. **BigQuery Data Modeling**
- **Fact and Dimension Tables**: Designed for scalability and efficiency.
- **Optimized Queries**: Enable quick analysis of business metrics.

---

### 5. **Looker Studio Dashboard**
The dashboard showcases:
- **Trends**: Cab usage over time.
- **KPIs**: Revenue, trips per day, driver efficiency.
- **Performance Metrics**: Trip duration, customer satisfaction.

---

## 📈 **Dashboard Features**
- **Ride-sharing Data**: Tracks revenue, trip counts, and more.
- **Geospatial Insights**: Maps showing service coverage.
- **KPIs**: Monitors performance and efficiency.
- **Time-Based Analysis**: Breaks down data by hour or day.

---

## 📋 **How to Run the ETL Pipeline**

### Prerequisites
1. **Google Cloud VM**: Access to a Google Cloud account and VM.
2. **Mage Installation**: Install from [Mage's Official Site](https://www.mage.ai/).
3. **BigQuery Access**: Set up BigQuery for data storage.

### 🐙 Clone the Repository
```bash
git clone https://github.com/ahtisham73/CabLytics.git
cd Cablytics
```

### 🔧 Set Up Mage and Google Cloud VM
1. Launch a VM on Google Cloud.
2. Install Mage on the VM.
3. Connect Mage to Google Cloud VM and BigQuery.

### 🚀 Run the ETL Pipeline
1. Use Mage to create a pipeline for data ingestion, transformation, and loading into BigQuery.

### 📊 Query the Data
1. Run SQL queries from `docs/Query2.md` in BigQuery.
2. View visualizations in the Looker Studio dashboard.

💡 **Pro Tip**: If Mage fails, check your VM’s internet connection—Google Cloud can be picky! 😄

---

## 📅 **Conclusion**
Cablytics delivers a powerful solution for cab service analytics, blending ETL pipelines, BigQuery modeling, and Looker Studio dashboards. It’s a solid project to showcase your data engineering skills in exams! Future enhancements could include real-time data streams or predictive analytics.

---

## 📜 **References**
- [Mage Documentation](https://www.mage.ai/)
- [Google Cloud BigQuery](https://cloud.google.com/bigquery)
- [Looker Studio](https://lookerstudio.google.com/)

---

## 📝 **Future Work**
- **New Data Sources**: Add customer feedback or traffic data.
- **Advanced Analytics**: Predict demand with machine learning.
- **Real-Time Updates**: Stream data for live dashboards.

---

## 🙌 **Contributing**
Got ideas? Fork the repo, make changes, and submit a pull request! Let’s build smarter together. 😊

⭐ **Star the repo** if you find it useful!

---

## 📨 **Contact**
**Maintainer**: Ahtisham Sudheer  
📧 Email: [ahtishamsudheer@gmail.com](mailto:ahtishamsudheer@gmail.com)  
Reach out for questions or feedback!

---

🌟 **Fun Fact**: Cablytics turns raw data into a cab company’s superpower—think of it as giving taxis a brain! 🧠🚖
