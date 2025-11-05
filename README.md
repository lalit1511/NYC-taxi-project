# 🚖 NYC Taxi Trips Data Analysis (Comprehensive EDA)

## 🧭 Overview  
This project presents an in-depth **Exploratory Data Analysis (EDA)** of **New York City Taxi Operations**, revealing hidden insights into trip demand, fare behavior, passenger patterns, and spatial activity.  
Using **Python, Pandas, Matplotlib, Seaborn, and GeoPandas**, the analysis uncovers meaningful trends to support **operational efficiency, pricing optimization, and dispatch management**.

---

## 📊 Project Objectives
- Analyze **trip patterns** across hours, days, and months.  
- Identify **busiest pickup and dropoff zones** using NYC Taxi Zone shapefiles.  
- Study relationships between **distance, fare, and tips**.  
- Understand **payment preferences** and their impact on revenue.  
- Generate **data-driven recommendations** to optimize routes, pricing, and fleet allocation.

---

## 🧠 Key Insights
- 🕐 **Peak Hours:** Strong morning (8–9 AM) and evening (6–8 PM) travel demand.  
- 📍 **High-Demand Zones:** Midtown Manhattan, JFK Airport, and Times Square dominate trip counts.  
- 💵 **Fare vs. Distance:** Fares grow linearly with distance, while tips show behavioral variance.  
- 💳 **Payment Patterns:** Credit cards account for the majority of revenue.  
- 🌃 **Night Activity:** Significant night traffic to and from airport zones.  
- 🚕 **Vendor Comparison:** Minor fare structure differences observed across providers.

---

## 🗺️ Geo-Spatial Analysis
Integrated NYC Taxi Zone shapefiles (`.shp`, `.dbf`, `.shx`, `.prj`) to:
- Map **pickup/dropoff frequencies** across zones.  
- Create **heatmaps** showing trip density and night activity.  
- Visualize **fare-per-mile** variations across boroughs.

**Tools Used:** `GeoPandas`, `Matplotlib`, `Shapely`

---

## ⚙️ Tech Stack
| Category | Tools |
|-----------|--------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Geospatial Analysis | GeoPandas |
| Environment | Jupyter Notebook / Google Colab |
| File Formats | `.parquet`, `.shp`, `.dbf`, `.shx`, `.prj` |

---

## 🧩 Workflow Summary
1. **Data Loading & Cleaning** – Imported and formatted trip data.  
2. **Time-Based Analysis** – Hourly, daily, and monthly trip distributions.  
3. **Fare & Tip Exploration** – Relationship between fares, distances, and passenger counts.  
4. **Payment Type Study** – Mode-wise fare and tip comparison.  
5. **Spatial Analysis** – Merged shapefile data for zone mapping.  
6. **Nighttime Activity** – Identified top 10 night-active zones.  
7. **Insight Generation** – Strategic recommendations based on findings.

---

## 🧾 Recommendations

### 🚗 Routing & Dispatch Optimization
- Focus fleet deployment in **Midtown, Times Square, and JFK** during peak hours.  
- Use **dynamic redistribution** to balance idle taxis during off-peak times.  

### 🏙️ Strategic Cab Positioning
- Position cabs near **airport and downtown zones at night**.  
- Use data-driven demand forecasting to ensure balanced coverage across boroughs.  

### 💰 Pricing Strategy
- Implement **dynamic pricing** for high-demand hours and routes.  
- Offer **fare incentives** for underutilized time slots to maintain steady ridership.  

---

## 📁 Repository Structure
📦 NYC_Taxi_Analysis
├── NYC_Taxi_Sample_5pct.parquet
├── taxi_zones.shp / .dbf / .shx / .prj
├── NYC_Taxi_Analysis.ipynb
├── Report_NYC_Taxi_Operations_Starter.docx
├── Output_Visuals/
│ ├── hourly_trends.png
│ ├── night_zones_heatmap.png
│ └── fare_vs_distance.png
└── README.md



