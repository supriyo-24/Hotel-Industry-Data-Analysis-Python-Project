# 🏨 Hotel Industry Data Analysis  
## 🇮🇳 Indian Hospitality Market — Exploratory Data Analysis (EDA)

---

## 📌 Project Overview

This project presents a complete **exploratory data analysis (EDA)** of the **Indian hotel industry**, aimed at understanding hotel supply, quality distribution, property types, geographic concentration, and the scarcity of premium hospitality offerings.

The analysis is implemented fully in **Python using Pandas and Matplotlib** within a Jupyter Notebook and is supported by a visual report.

---
## 🛠️ Tools & Environment

- Python  
- Jupyter Notebook  
- Pandas  
- Matplotlib  

---

## 📊 Dataset Summary

| Metric | Value |
|------|------|
| Raw Records | 5,000 |
| Cleaned Records | 2,571 |
| Initial Columns | 15 |
| Final Columns Used | 6 |

### Final Columns
- Property Name  
- City  
- State  
- Star Rating  
- Room Count  
- Property Type  

---

## 🧹 Data Cleaning & Preprocessing

1. Loaded Excel data using Pandas  
2. Dropped irrelevant columns  
3. Standardized star ratings  
   - Converted text values (e.g., “3 Star Hotel”) into numeric ratings  
4. Removed rows with missing or invalid values  
5. Ensured numeric consistency for analysis  

✅ Final clean dataset contains **2,571 verified hotel records**.

---

## 📈 Descriptive Statistics

| Metric | Value |
|------|------|
| ⭐ Average Star Rating | **2.46 / 5** |
| 🛏️ Average Rooms per Hotel | **28.1** |
| 📉 25th Percentile (Rooms) | **14** |
| 🏢 Largest Hotel | **340 rooms** |

🔍 **Insight:**  
The Indian hotel market is dominated by **small, budget-oriented properties**.

---

## 🏙️ City-Level Market Analysis

### Top Cities by Hotel Count
- Jaipur (highest supply)
- Kolkata
- Kochi
- New Delhi
- Gangtok

📌 Tier-2 tourist destinations compete strongly with metro cities in hotel volume.

---

## 🗺️ State-Level Supply Distribution

| Rank | State | Hotels |
|----|------|------|
| 1️⃣ | Rajasthan | 436 |
| 2️⃣ | Kerala | 249 |
| 3️⃣ | West Bengal | 222 |
| 4️⃣ | Tamil Nadu | 195 |
| 5️⃣ | Himachal Pradesh | 181 |

---

## ⭐ Property Type Quality Analysis

| Property Type | Avg Star Rating |
|-------------|----------------|
| 🏖️ Resort | **2.94** |
| 🏨 Hotel | 2.41 |
| 🏠 Lodge | 2.40 |
| 🏢 Serviced Apartment | 2.25 |
| 🏡 Homestay | 1.75 |
| 🚪 Guest House | **1.60** |

📉 Guest Houses and Homestays show the **lowest perceived quality**, indicating a strong upgrade opportunity.

---

## 💎 Premium Segment Analysis

### Definition of “True Luxury”
- ⭐ Star Rating ≥ **4.0**
- 🛏️ Room Count > **50**

| Metric | Value |
|------|------|
| Premium Hotels | **114** |
| Market Share | **4.4%** |

📌 **Conclusion:**  
True luxury hospitality is **rare** in the Indian hotel market.

---

## 📍 Quality vs Quantity Insight

- Rajasthan → High quantity, average quality  
- Kerala & Goa → Lower volume, higher quality focus  

🎯 Markets prioritizing quality outperform volume leaders in hospitality experience.

---

## 📊 Visualizations Included

The notebook generates multiple visualizations:
- Top cities by hotel count  
- Star rating distribution  
- Property type distribution  
- Average room count by property type  
- State-wise average hotel ratings  
- Premium vs non-premium segmentation  

All charts are compiled in **Hotel-Industry-Data-Analysis.pdf**.

---

## 📌 Strategic Recommendations

- Avoid oversaturated markets like Jaipur  
- Invest in **Resort properties** for higher customer satisfaction  
- Upgrade **Guest Houses and Homestays**  
- Target under-served tourist regions with growth potential  

---

## 🔮 Future Scope

- Price-based segmentation  
- Seasonal demand analysis  
- Review sentiment analysis  
- Revenue and profitability modeling  

---

## 👤 Author

**Supriyo Maity**  

---

## 🏷️ Tags

#Python #EDA #DataAnalysis #HotelIndustry #HospitalityAnalytics #IndiaMarket #Pandas #Matplotlib #JupyterNotebook
