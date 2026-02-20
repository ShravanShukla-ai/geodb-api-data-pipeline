![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green?logo=pandas)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)
![API](https://img.shields.io/badge/API-GeoDB-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
---

# 🌍 GeoDB API Data Pipeline  
### Designing an End-to-End API Data Extraction Workflow with Pagination & MySQL Integration

---

## 📌 Project Overview

This project demonstrates a real-world API data engineering workflow using the GeoDB Cities API (RapidAPI).

The pipeline extracts data using pagination logic, processes JSON responses into structured format using Pandas, and stores the data into a MySQL database.

A total of **3305 administrative division records** were successfully fetched and exported.

---

## 🏆 Project Highlights

- ✅ API Authentication using RapidAPI
- ✅ Pagination Handling (limit & offset logic)
- ✅ Rate-limit and Error Handling
- ✅ JSON → Pandas DataFrame Transformation
- ✅ MySQL Database Integration using SQLAlchemy
- ✅ CSV Export for Portability
- ✅ End-to-End Data Engineering Mini Pipeline

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Programming |
| Requests | API Communication |
| Pandas | Data Processing |
| SQLAlchemy | Database Integration |
| PyMySQL | MySQL Connectivity |
| MySQL Workbench | Database Management |
| RapidAPI | Data Source |

---

## 📊 Dataset Details

- **Source:** GeoDB API (RapidAPI)
- **Data Type:** Administrative Divisions
- **Total Records Fetched:** 3305
- **Format:** JSON → Structured DataFrame → MySQL Table → CSV

---

## ⚙️ Project Workflow

1. Connect to GeoDB API using authentication key
2. Implement pagination using `limit` and `offset.`
3. Handle API rate limits and connection errors
4. Convert API response into Pandas DataFrame
5. Store processed data into the MySQL database
6. Export final dataset as CSV file

---

## 📂 Repository Structure

geodb-api-data-pipeline/
│
├── api_fetch.ipynb
├── admin_divisions_3305_records.csv
├──README.md


---

## 🚀 Key Learnings

- Real-world API integration
- Pagination strategy implementation
- Handling rate limits & API failures
- Data transformation best practices
- Database storage via SQLAlchemy
- Building reproducible data pipelines

---

## 📈 Why This Project Matters

This project reflects practical skills required in:

- Data Engineering
- Data Analytics
- Backend Data Integration
- API Data Processing
- ETL Workflow Design

---

## 👨‍💻 Author

**Shravan Shukla**  
Aspiring Data Analyst | Data Engineering Enthusiast  

---

⭐ If you found this project useful, feel free to star the repository.
