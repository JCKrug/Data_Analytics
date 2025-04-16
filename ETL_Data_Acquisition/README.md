# Gans E-Scooter Case Study – ETL Pipeline for Smart Mobility

## 📖 Project Overview
Gans is a fictive, innovative startup building an e-scooter-sharing system for global cities. This project focused on designing a local **ETL (Extract, Transform, Load)** pipeline to gather and structure relevant data for **predicting scooter usage patterns** and informing operational decisions.

---

## 🏙️ Business Context
Success in the e-scooter market (e.g., competitors like TIER and Bird) depends not only on sustainability, but on **smart fleet distribution**. Gans identified several urban usage patterns and inefficiencies:

- 🚴‍♀️ Uphill rides / downhill walks in hilly areas  
- ☀️ Morning migrations from suburbs to city centers  
- 🌧️ Reduced demand during rainy weather  
- 🧳 Tourist hotspots needing high scooter availability  

To address these asymmetries, Gans considers using **truck relocation** or **user-based incentives**. For either approach, a **robust data infrastructure** is essential.

---

## 🧰 Project Scope
Build an end-to-end **ETL pipeline** to extract, clean, and store data for further analysis.
---

## ⏰ Case Study Duration
**3 days** (February 2025)
---

### ✅ Key Objectives
- **Data Collection**  
  - 🌐 Web scraping from public sources (e.g. Wikipedia)  
  - 🔌 API integration for structured data retrieval  
- **Data Transformation**  
  - 🧹 Clean and normalize data using `pandas` in Python  
- **Data Storage**  
  - 🗃️ Store processed data in a local SQL database  

---

## 🛠 Technologies Used
- Python (for scripting and orchestration)  
- `pandas` (data wrangling)  
- `BeautifulSoup` (web scraping)  
- API access (external data ingestion)  
- SQL (for structured storage and querying)

---

## 📦 Deliverables
A fully functional, modular **ETL pipeline** built in Python with:
- Cleaned and structured datasets
- Integrated API/web scraping logic
- SQL schema for persistent storage

> 🧑‍💻 All code is available in this GitHub repository.
- [Scarping Cities data via wikipedia.com](https://github.com/JCKrug/Data_Analytics/blob/main/ETL_Data_Acquisition/1_Cities_data.ipynb)
-  Extract data from web via API ([Weather](https://github.com/JCKrug/Data_Analytics/blob/main/ETL_Data_Acquisition/2_Weather_data.ipynb), [Airports](https://github.com/JCKrug/Data_Analytics/blob/main/ETL_Data_Acquisition/3_Airports_data.ipynb), [Flights](https://github.com/JCKrug/Data_Analytics/blob/main/ETL_Data_Acquisition/4_Flights_data.ipynb))
-  [Create database & tables via SQL](https://github.com/JCKrug/Data_Analytics/blob/main/ETL_Data_Acquisition/GANS_Database_ETL.sql)
-  [Schema database via SQL](https://github.com/JCKrug/Data_Analytics/blob/main/ETL_Data_Acquisition/Schema_Gans_MySQL.pdf)

---

## ⚠️ Key Challenges & Learnings
- Inconsistent data formats across sources  
- Managing authentication for APIs  
- Ethical web scraping practices  
- Automating the full data pipeline from collection to storage  

---

## 🚫 Out of Scope
To maintain focus, the following areas were not covered:  
- Data lake or warehouse architecture  
- Big Data or parallel processing systems  

---

## 🏁 Conclusion
This project demonstrates **practical data engineering skills** and forms the foundation for future **predictive analytics** at Gans. By building a working ETL pipeline, we create a reliable data source for smarter scooter fleet management.

Feel free to explore the code, raise issues, or share your thoughts! 🚀



