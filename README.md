# earthquake

## 🌍 Problem Statement

Despite the Philippines’ vulnerability to earthquakes due to its location in the Pacific Ring of Fire, there remains a lack of long-term spatial and temporal analysis of seismic patterns to inform disaster preparedness. 

Existing solutions focus on real-time monitoring rather than predictive or pattern-based risk assessment. This research addresses the gap by applying geospatial clustering techniques to identify statistically significant earthquake hotspots, aiming to support data-driven decisions in evacuation planning and infrastructure development.

---

## 🎯 General Objective

To analyze **where and when** earthquakes commonly occur in the Philippines using clustering techniques, and to use this information to help improve evacuation planning and disaster preparedness.

---

## ✅ Specific Objectives

- To gather and clean historical earthquake data from reliable sources, focusing on key information such as:
  - Date and time  
  - Latitude and longitude  
  - Depth (km)  
  - Location  
  - Magnitude  

- To identify areas and time periods with frequent earthquakes by applying spatial and temporal clustering techniques such as:
  - **Getis-Ord Gi***  
  - **Anselin Local Moran’s I**  
  - **DBSCAN**  

- To map the earthquake hotspots using **Geographic Information Systems (GIS)** and visualize their relationship with existing evacuation centers.

- To evaluate how close and accessible the evacuation centers are to the high-risk areas identified in the hotspot analysis.

- To give recommendations on where to place new evacuation centers or improve current ones, based on the identified risks and spatial gaps.

- To provide practical insights for **Local Government Units (LGUs)** and disaster response agencies by sharing visual maps and summaries of the findings.

---

## ⚙️ Tools & Techniques

- Python
- Pandas, NumPy
- Scikit-learn (KMeans, DBSCAN)
- PySAL (Getis-Ord Gi*, Anselin Local Moran’s I)
- GeoPandas
- Matplotlib, Seaborn
- Plotly (for interactive GIS mapping)

---

## 📂 Project Structure

```plaintext
📁 data/
    📄 raw_earthquakes.csv
    📄 cleaned_earthquakes.csv
📁 notebooks/
    📄 01_data_cleaning.ipynb
    📄 02_clustering_analysis.ipynb
📄 README.md
📄 requirements.txt
