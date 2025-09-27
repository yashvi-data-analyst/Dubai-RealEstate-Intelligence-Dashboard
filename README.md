# 🏙️ Dubai Real Estate Intelligence Dashboard  
**LabMentix Internship – Week 2 Project**  

---

## 📖 Project Overview  
This project analyzes Dubai’s housing dataset (~50K listings) and builds a **data pipeline from Python → Cleaned Dataset → Power BI Dashboard → Insights Report & Video**.  
The goal is to generate **actionable insights** for:  
- 🏦 Investors  
- 🏠 Real Estate Agents  
- 🏛️ Policymakers  

---

## 🗂️ Repository Structure  
Dubai-RealEstate-Intelligence-Dashboard/
│── data/
│ └── housing_price_dataset.csv # Raw dataset (input)
│ └── dubai_housing_enriched.csv # Cleaned dataset (output)
│
│── notebooks/
│ └── dubai_housing_cleaning.ipynb # Jupyter Notebook for data cleaning
│
│── dashboard/
│ └── LabMentix_Week2_Dubai_Housing_Dashboard.pbix # Power BI dashboard file
│
│── report/
│ └── LabMentix_Week2_Insights.pptx # Insights Presentation (PPT)
│ └── LabMentix_Week2_Insights.pdf # Insights Slide (PDF export)
│
│── video/
│ └── Dubai_Housing_Dashboard.mp4 # Walkthrough Video (optional)
│
│── README.md

---


---

## 🐍 Data Cleaning & Enrichment (Python – Jupyter Notebook)  
Performed using **Pandas, Numpy** in `dubai_housing_cleaning.ipynb`:  
- ✂️ Removed duplicates & invalid rows  
- 🔄 Converted data types (numeric/text)  
- 🔧 Handled missing values (median fill + 'Unknown')  
- ➕ Added calculated fields:  
  - `Price per Sqft = price / size`  
  - `Property Age = 2025 – year_built`  
  - `Listing Category = Budget / Mid-Range / High-End` (quantiles)  

**Output:** `dubai_housing_enriched.csv` → Ready for Power BI 🚀  

---

## 📊 Dashboard Development (Power BI)  

### KPI Cards  
- 📌 Total Listings  
- 📌 Average Price  
- 📌 Average Size (sqft)  
- 📌 Average Price per Sqft  
- 📌 Highest Price  

### Visuals Used  
- 🥧 Donut Chart → % Split by Listing Category  
- 📊 Bar Chart → Average Price by Location (Urban/Suburb/Rural)  
- 📈 Line Chart → Price Trend by Year Built  
- 🧩 Treemap → Listings by Location & Bedrooms  
- 🏠 Column Chart → Listings by Bedrooms  
- 🗺️ Map Visual → Average Price by Location (geospatial view)  

### Interactivity  
- 🔍 Filters: Location, Bedrooms, Categories, Price Range  
- 🎯 Custom colors (Urban=Blue, Suburb=Green, Rural=Orange)  
- 📌 Drill-downs & tooltips for details  

---

## 📝 Key Insights  
- 🏙️ **Urban** → Highest Avg Prices → Luxury Hub  
- 🏠 **Suburb** → Largest no. of listings (mainly 2–3 BHK, Mid-range homes)  
- 🌿 **Rural** → Budget-friendly homes, lowest price per sqft  
- 📈 Properties built post-2000 = Higher priced & more volatile  

---

## 💡 Recommendations  
- **Investors:** Focus Urban luxury (5BHK) for premium ROI 💰  
- **Agents:** Target Suburb 2–3 BHK for faster sales volumes 🏡  
- **Policymakers:** Support Affordable Housing in Urban & manage Suburb oversupply ⚖️  

---

## 📑 Deliverables  
- ✅ [Power BI Dashboard (.pbix)](./dashboard/LabMentix_Week2_Dubai_Housing_Dashboard.pbix)  
- ✅ [Insights Presentation (.pptx)](./report/LabMentix_Week2_Insights.pptx)  
- ✅ [Insights Report (.pdf)](./report/LabMentix_Week2_Insights.pdf)  
- 🎥 [Video Walkthrough](./video/Dubai_Housing_Dashboard.mp4)  

---

## 🖼️ Dashboard Preview  
👉 Full interactive dashboard can be explored by opening the `.pbix` file included in the **/dashboard/** folder.  

*(Screenshot not added here because Power BI file is already provided inside repo)* 🔥  

---

## 🙌 Acknowledgement  
This project was developed as part of **LabMentix Internship – Week 2**.  
It demonstrates end-to-end workflow: **Python preprocessing → Power BI dashboarding → Business Insights → Presentation & Video**.  

---

### ❤️ Made by *Yashvi Verma*  
