# MySQL-ETL-Service-Dashboard

This repository contains a Power BI dashboard project that provides insightful analytics and key trends based on service data processed through a complete ETL (Extraction, Transformation, and Load) pipeline using MySQL. The dashboard visualizes service performance metrics to support data-driven decision-making.

## 🚀 Project Overview

This dashboard was built to analyze and visualize key trends from service data sourced from multiple Excel files. The data was processed using a structured ETL workflow in MySQL and then visualized in Power BI for dynamic reporting and business insights.

## 📊 Dashboard Highlights

- Interactive and visually appealing dashboards
- Key trends and patterns in service performance
- Slicers and filters for flexible analysis
- Clean, intuitive layout for users

## 🔄 ETL Process in MySQL

### 1. **Extraction**
- Imported multiple Excel files into MySQL Workbench

### 2. **Transformation**
- Cleaned and standardized the data
- Combined relevant columns from each table
- Created a unified **master table** to consolidate information

### 3. **Load**
- Loaded the final master table into **Power BI**
- Built data models and visuals using Power BI Desktop

## 🧰 Tools & Technologies

- **MySQL Workbench** – For database setup and ETL operations
- **Microsoft Excel** – Source data files
- **Power BI Desktop** – For data modeling and dashboard creation

## 📁 File Structure

- `CAWA_Services_Dashboard.pbix` – Power BI dashboard file
- `README.md` – Project documentation


## ✅ How to Use

1. Clone this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Explore the dashboard and interact with filters and visuals
4. (Optional) Connect Power BI to your own MySQL database if re-running the pipeline

## 📌 Notes

- Ensure the **MySQL ODBC driver** is installed if you plan to connect Power BI directly to MySQL
- This ETL process is scalable – you can add new Excel files and rebuild the master table using the same structure

## 📬 Feedback & Contributions

If you have any suggestions, issues, or ideas to enhance this project, feel free to open an issue or submit a pull request.

---

**Built with ❤️ using MySQL + Power BI**

