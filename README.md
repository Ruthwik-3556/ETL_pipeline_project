# ETL_pipeline_project
implemented a modular ETL pipeline where data is extracted from a CSV file, transformed to handle missing values and enforce data integrity using Pandas, and loaded into a SQLite database. The processed data was validated using SQL queries and visualized using Matplotlib

# 📊 ETL Pipeline Project (CSV → SQLite Database)

## 📌 Project Overview
This project demonstrates a complete **ETL (Extract, Transform, Load) pipeline** using Python.  
Employee data is extracted from a CSV file, cleaned and transformed using Pandas, and loaded into a SQLite database.  
The project is implemented in a **modular and scalable structure**, following real-world data engineering practices.

---

## 🛠️ Tools & Technologies
- **Python 3**
- **Pandas** – Data extraction & transformation
- **SQLite** – Lightweight relational database
- **Jupyter Notebook** – Development environment
- **Matplotlib** – Data visualization

---

## 📂 Project Structure
ETL_Pipeline_Project/
│
├── data.csv # Source CSV file
├── extract.ipynb # Extract module
├── transform.ipynb # Transform module
├── load.ipynb # Load module
├── database.ipynb # Database connection & table creation
├── main.ipynb # Main ETL pipeline controller
├── company.db # SQLite database
├── ETL_Project_Report.pdf# Project report with visualizations
└── README.md # Project documentation

yaml
Copy code

---

## 🔁 ETL Pipeline Workflow

CSV File
↓
Extract (read CSV using Pandas)
↓
Transform (handle missing values, clean data)
↓
Load (store into SQLite database)
↓
Database Table

yaml
Copy code

---

## 🔍 ETL Stages Explained

### 1️⃣ Extract
- Reads employee data from `data.csv`
- Loads data into a Pandas DataFrame

### 2️⃣ Transform
- Handles missing values in `age` and `salary`
- Converts `joining_date` to datetime format
- Enforces correct data types
- Applies basic data validation

### 3️⃣ Load
- Creates a SQLite database (`company.db`)
- Inserts cleaned data into the `employees` table

---

## 📊 Data Visualizations
The following visualizations are included in the project report:
- **Average Salary by Department** (Bar Chart)
- **Age Distribution of Employees** (Histogram)

---

## ▶️ How to Run the Project

1. Ensure all `.ipynb` files are in the same directory
2. Open **Jupyter Notebook**
3. Open and run `main.ipynb`
4. The ETL pipeline will execute automatically
5. Final data will be stored in `company.db`

---

## ✅ Output
- Cleaned employee data stored in SQLite database
- Verified using SQL queries
- Visual insights generated using Matplotlib
- Complete documentation in PDF format

---

## 🧠 Viva / Evaluation Summary
> “This project implements a modular ETL pipeline that extracts data from a CSV file, transforms it using Pandas for data quality and consistency, and loads it into a SQLite database. The processed data is validated and visualized for analysis.”

---

## 📌 Conclusion
This project successfully demonstrates core data engineering concepts including:
- Data extraction
- Data cleaning & transformation
- Database loading
- Data visualization
- Modular project design

---

## 👤 Author
**Ruthwik Chetan Naik**

---

## 📄 License
This project is created for academic and educational purposes.
