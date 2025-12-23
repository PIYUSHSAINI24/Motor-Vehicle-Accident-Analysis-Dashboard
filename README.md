# 🚗 Motor Vehicle Accidents Analysis Dashboard – Power BI  

## 📌 Project Overview  
Motor vehicle accidents are a major public safety concern worldwide. This project focuses on analyzing real-world **motor vehicle collision data** using **Microsoft Power BI** to uncover meaningful insights such as accident trends, severity levels, high-risk locations, time patterns, and the impact on vulnerable road users (pedestrians, cyclists, and bikers).

The dashboard converts raw accident records into **interactive visuals** that support data-driven decision-making and road safety awareness.

---

## 🎯 Objectives  
- Analyze accident trends over time  
- Identify high-risk locations and accident hotspots  
- Study accident distribution across time bands (Morning/Afternoon/Evening/Night)  
- Understand involvement of vehicle types and contributing causes  
- Assess injuries and fatalities with focus on vulnerable users  
- Build a clean, insightful, and interactive Power BI dashboard  

---

## 📂 Dataset Description  
Each record in the dataset represents a **single accident event**.

### Key Columns  
- **CRASH DATE / CRASH TIME** – accident timestamp  
- **BOROUGH / ZIP CODE** – accident location  
- **LATITUDE / LONGITUDE** – used for mapping  
- **VEHICLE TYPE CODE** – vehicle involved  
- **CONTRIBUTING FACTOR** – reason of accident  
- **Persons Injured / Killed**  
- **Pedestrians, Cyclists, Motorists Injured & Killed**

---

## 🛠️ Tools & Technologies  
- **Power BI Desktop**  
- **Power Query** (Data Cleaning)  
- **DAX (Data Analysis Expressions)**  
- **Star Schema Data Modeling**

---

## 🧹 Data Preprocessing  
✔ Removal of irrelevant and duplicate columns  
✔ Handling missing values  
✔ Standardization of categorical fields  
✔ Derived fields: Year, Month, Day, Time Band  
✔ Validation for accuracy and consistency  

---

## 🏗️ Data Modeling  
A **Star Schema** was implemented.

### Fact Table  
- Fact_Crashes (Accident-level metrics)

### Dimension Tables  
- Dim_Date  
- Dim_Time  
- Dim_Location  
- Dim_Vehicle  
- Dim_Cause  

Relationships: One-to-Many with single filter direction

---

## 📊 Dashboard Features  
- KPI Cards: Total Accidents, Injuries, Fatalities, Vulnerable Users  
- Line Charts: Yearly & Monthly trends  
- Time Band Analysis  
- Borough-wise Accident Analysis  
- Vehicle Type & Cause Analysis  
- Vulnerable User Insights  
- Accident Density Map  
- Interactive Slicers: Year, Day, Time Band, Location  

---

## 🔍 Key Insights  
- Higher accident risk during **evening and afternoon**  
- Specific boroughs show higher accident density  
- Motor vehicles dominate accidents, but pedestrians/cyclists are highly vulnerable  
- Human behavior factors like distraction and failure to yield play major roles  

---

## ✅ Conclusion  
This project demonstrates how Power BI can transform raw accident data into **meaningful insights**. The dashboard supports accident monitoring, safety planning, and awareness initiatives while showcasing practical implementation of **data analytics, modeling, and visualization concepts**.

---

## 🚀 Future Enhancements  
- Integration of weather & traffic data  
- Predictive accident risk modeling  
- Real-time accident monitoring  
- Advanced geospatial analysis  

---

## 🙌 Acknowledgment  
This project was completed as part of **Data Analytics with Power BI (INT374)** coursework.
