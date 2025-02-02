
---

# 🏥🏠 **Spatial Analysis of Hospitals, Shelters & Social Facilities in Ireland**  

## 📌 **Project Overview**  
This project explores the **spatial distribution** of hospitals, shelters, and social facilities in Ireland. Using **PostGIS & QGIS**, we analyze **how accessible** these facilities are and how they interact with each other.  

The goal? **Better urban & rural planning** 🏙️🌿 and improved emergency response 🚑.  

## 📂 **Datasets Used**  
We work with the following datasets 📊:  
- 🏥 **Hospitals** – Locations of medical facilities.  
- 🏠 **Shelters** – Emergency & social shelters.  
- 🏫 **Social Facilities** – Community centers, care homes, etc.  
- 🚏 **Bus Stops** – Public transport locations.  

## 🛠️ **Tools & Technologies**  
- 🗄️ **PostgreSQL + PostGIS** – For running powerful **spatial queries**.  
- 🗺️ **QGIS** – To visualize & analyze geographic data.  

## 🔍 **Key SQL Queries Implemented**  
Here’s what we can do with **SQL + PostGIS**:  

1️⃣ **Find Hospitals Near a Location** 🏥📍 → Hospitals within **8km of a point in Dublin**.  
2️⃣ **Find Social Facilities in Cork** 🏫📍 → Social centers within **3km of Cork city center**.  
3️⃣ **Find Hospitals Close to Shelters** 🏥🏠 → Hospitals & shelters within **5km** of each other.  
4️⃣ **Find Emergency Shelters Near Hospitals** 🚨🏠 → Shelters **within 10km** of hospitals.  
5️⃣ **Measure Distance Between Two Shelters** 📏🏠🏠 → Calculates the **straight-line distance**.  
6️⃣ **Find Social Facilities Near a Location** 🏫📌 → Social centers **within 4km** in Dublin.  
7️⃣ **Create a Circular Zone for Shelters** 🔵🏠 → Defines a **4km boundary** around all shelters.  
8️⃣ **Generate a Heat Map for Social Facilities** 🔥🏫 → Visualizes **hotspots** of social services.  
9️⃣ **Create Bounding Polygons for Social Facilities** 🛑🏫 → Defines coverage areas in **Dublin & Cork**.  
🔟 **Generate a Heat Map for Shelters** 🔥🏠 → Shows **high & low-density shelter areas**.  

## 🚀 **How to Use**  
1️⃣ **Clone the Repository**:  
   ```sh
   git clone <repository_url>
   cd <repository_folder>
   ```  
2️⃣ **Import SQL Files** into **PostgreSQL with PostGIS**.  
3️⃣ **Open QGIS** to visualize the maps and analyze spatial relationships.  

## 📊 **Insights & Impact**  
✅ Identify **healthcare & shelter accessibility gaps** 🚑  
✅ Help **urban planners & emergency responders** 📍  
✅ Use **QGIS** to see **real-world patterns & improvements** 🌍  

## 👨‍💻 **Contributor**  
- **Subramanyam Palagiri** 🎓  

## 📜 **License**  
📝 This project is licensed under the **MIT License**.  

---

