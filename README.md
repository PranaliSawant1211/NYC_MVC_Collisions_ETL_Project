# NYC Motor Vehicle Collisions – End-to-End ETL and Analytics Project

## 🚦 Project Overview

This project demonstrates a complete **ETL pipeline and business intelligence workflow** designed to analyze motor vehicle collisions in **New York City**. Using real-world open data, the project handles raw ingestion, transformation, modeling, and dashboard visualization to uncover patterns and insights into NYC traffic incidents.

From cleaning over **2 million collision records** to visualizing location-based accident hotspots and time-based trends, this project exemplifies a real-life data engineering and analytics use case integrating **Talend**, **Alteryx**, **ER Modeling**, and **Tableau**.

---

## 📂 Project Structure

| Folder          | Description |
|------------------|-------------|
| `Alteryx`        | Contains data profiling and transformation workflows created in Alteryx Designer. Used for initial data exploration and cleansing. |
| `Talend`         | Contains Talend ETL jobs used for large-scale data ingestion, filtering, deduplication, and transformation pipelines. |
| `Data Models`    | Includes both **physical** and **dimensional** models representing normalized and analytical schemas. Designed using ER modeling tools. |
| `Tableau`        | Contains published Tableau dashboards showing KPI visualizations, heatmaps, and time-trend analyses based on the cleaned dataset. |

---

## 📊 Dataset Information

- **Source**: [NYC Open Data - Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- **Records Processed**: 2 million+
- **Key Fields**:
  - Crash Date, Time, Borough, ZIP Code
  - Latitude/Longitude (Geolocation)
  - Number of Persons Injured/Killed
  - Vehicle Types Involved
  - Contributing Factors (e.g., distracted driving, speeding)

---

## 🎯 Objectives

- Automate **data extraction and transformation** from NYC open data using Talend.
- Perform **data profiling and quality checks** with Alteryx.
- Design both **normalized** and **analytical data models** to support efficient reporting.
- Develop **interactive Tableau dashboards** for visualization and insights.
- Deliver a modular, end-to-end data pipeline ready for scaling.

---

## 🛠️ Tools & Technologies

- **Talend Open Studio** – ETL for large-volume data extraction and transformation.
- **Alteryx Designer** – Used for profiling, pre-cleaning, and visual transformations.
- **ER/Studio or DM1** – For physical and dimensional data model design.
- **Tableau** – Interactive dashboards for stakeholders and public safety analytics.
- **GitHub** – Project versioning and collaboration.

---

## 🔍 Features & Deliverables

### ✅ ETL & Cleansing
- Extracted raw NYC collision data (CSV/API).
- Filtered invalid dates, null coordinates, and duplicates.
- Normalized borough names, ZIP codes, and contributing factor values.
- Handled edge cases such as multi-vehicle collisions and geolocation mismatches.

### 📐 Data Modeling
- **Physical Model**:
  - Designed for data integrity and storage efficiency.
  - Normalized entities: Crash, Vehicle, Person, Location, Time.
- **Dimensional Model**:
  - Star schema supporting Tableau dashboards.
  - Fact tables: `FactCrash`, `FactInjury`
  - Dimensions: `DimLocation`, `DimTime`, `DimVehicle`, `DimCause`

### 📊 Dashboard Visualizations
- Built with **Tableau**:
  - Collision heatmaps by borough and ZIP code
  - Time-trend graphs (weekly, monthly)
  - Top contributing causes by time of day
  - Fatal vs non-fatal crash analysis

---

## 📈 Business Use Cases

- Inform city agencies to optimize patrol coverage and signal timing.
- Detect high-risk zones for accidents and prioritize road safety investments.
- Share transparent traffic incident data with the public and city planners.
- Support predictive analytics for proactive crash prevention.

---

## 💡 Skills Demonstrated

- **Data Integration** and ETL using Talend & Alteryx.
- **Data Modeling** for transactional and analytical use cases.
- **Data Visualization** and storytelling using Tableau.
- **Data Quality Assessment** and profiling workflows.
- Version control and collaboration via **GitHub**.

---

## 🚀 Future Enhancements

- Schedule daily ETL jobs using Talend scheduler or cron-based automation.
- Integrate external datasets like weather or construction zones for deeper analysis.
- Export model to Snowflake or Redshift for scalable querying.
- Add alerting features for real-time crash pattern detection.

---

## 🙋‍♀️ Author

**Pranali Sawant**  
📫 [LinkedIn](https://www.linkedin.com/in/pranalisawantt12/) | 📧 pranalisawantt12@gmail.com  
🚀 Passionate about using data engineering and BI tools to drive safer, smarter cities.

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---

⭐ If you found this project helpful or insightful, please ⭐ this repo and connect with me on LinkedIn!
