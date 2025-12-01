# Tourism Insights Dashboard

## 📊 Overview
This project is a **Tourism Insights Dashboard** developed as part of the DEPI graduation project.  
It provides a detailed analysis of hotel attributes, amenities, and service quality across countries and continents, helping stakeholders make informed decisions in the tourism sector.

---

## 🛠 Technologies

1. Data Collection & Preparation Layer

-Raw Data Gathering
Collecting hotel data including locations, amenities, and service quality.
Data received as structured tables suitable for analysis.

-Excel
Used for storing raw data, initial formatting, and optional basic cleaning
(checking duplicates, fixing missing values, etc.).

2. Data Management Layer

-SQL (Optional Enhancement)
SQL can be used for:

-Managing large datasets

-Performing filtering, grouping, or joining tables

-Preparing data before importing into Power BI
(Note: This step is optional but recommended for scalable projects.)

3. Data Transformation Layer

-Power Query
Used inside Power BI for transforming data:

Cleaning dataset

Standardizing formats

Creating additional calculated columns

Merging/transforming tables before loading into the data model

4. Visualization & Analytics Layer

-Power BI
Used for:

Building the dashboard

Creating relationships and data model

Designing interactive report pages

Writing DAX measures for deeper analytics

---

## 📁 Files in this Repository
- `Tourism Dashboard.pbix` — Final Power BI file containing the dashboard and data model  
- `tourism Data.xlsx` — Raw dataset used in the project  
- `Data_Dictionary.xlsx` — Complete data dictionary for columns, measures, and data model  
- `screenshots/` — Optional folder with dashboard screenshots  
- `Documentation.pdf` — Detailed project documentation  
- `Presentation.pptx` — Optional DEPI presentation slides

---

## 📋 Dataset Description
- **File:** `tourism Data.xlsx`  
- **Content:** Hotel information with attributes such as location, amenities, and service quality  
- **Columns:** Hotel Name, Continent, Country, City, Amenities Level, Has Air Conditioning, Has WiFi, Has Free Parking, Has Breakfast, Price, Service Quality  
- **Rows:** Each row represents one hotel  
- **No survey used** — dataset contains factual hotel data

---

## 🧹 Data Cleaning & Preparation
Basic cleaning steps performed before building the dashboard:
- Missing values in text columns filled with `"Unknown"`  
- Missing boolean values filled with `FALSE`  
- Numeric columns checked for validity; extreme or inconsistent values corrected  
- Duplicates removed  
- Boolean and numeric columns standardized  
- Optional calculated columns added: `Amenities Count`, `Price Level`, `Service Quality Level`

> These steps ensured a clean and consistent dataset ready for analysis in Power BI.

---

## 🎯 Segmentation
The dashboard includes segmentation based on:
- Continent  
- Country  
- Amenities Level  
- Price Level (Low / Medium / High)  
- Service Quality Level  

Optional personas can be derived:
- Budget Hotel Persona  
- Mid-Range Hotel Persona  
- Luxury Hotel Persona

---

## 🧮 Key Performance Indicators (KPIs)
- % Hotels with Air Conditioning  
- % Hotels with WiFi  
- % Hotels with Free Parking  
- % Hotels with Breakfast  
- Average Amenities per Hotel  
- Average Price by Level and Continent  
- Hotel Service Quality Score  
- Total Number of Hotels  
- Maximum / Minimum Amenities Count  

---

## 📊 Storytelling Focus
The dashboard highlights:
- Hotel service quality evaluation  
- Comparison between countries and continents  
- Correlation between price and amenities  
- Insights for tourism investment and service improvements

---

## 📌 Technical Details
- Full data model included in PBIX  
- All DAX measures listed in `Data_Dictionary.xlsx`  
- Relationships explained in Documentation.pdf  
- Optional calculated columns: `Amenities Count`, `Price Level`, `Service Quality Level`  
- Clean, professional theme applied throughout

---

## 🔒 Privacy & Ethics
- Dataset contains no personal identifiable information (PII)  
- No anonymization required

---

## 📝 License
- **MIT License** recommended for GitHub repository

---

## 📂 Recommended Repository Structure
