# 🌍 Land Cover Change Detection using Multispectral Images

This project focuses on **remote sensing and land cover analysis** using **multispectral satellite images**.  
It applies vegetation, water, and built-up indices to classify land cover and performs **urban change detection** between two different time periods.

---

## 📌 Features
- Upload and preprocess multispectral images (`.TIF / .TIFF`)  
- Compute key spectral indices:  
  - **NDVI** – Normalized Difference Vegetation Index (Vegetation/Forest)  
  - **NDWI** – Normalized Difference Water Index (Water Bodies)  
  - **NDBI** – Normalized Difference Built-up Index (Urban/Built-up Areas)  
- Classify land cover into five categories:  
  - Built-up Area 🏙️  
  - Water 💧  
  - Forest 🌲  
  - Vegetation 🌱  
  - Barren Land 🏜️  
- Calculate percentage distribution of each land cover type  
- Detect land cover changes between two images (e.g., 2016 vs 2023)  
- Generate:  
  - **Change Map** (visual representation of changed areas)  
  - **Change Matrix** (numerical analysis of land cover shifts)  
  - **Scatter Plot** (comparison of category-wise percentages)
    

---


📂 Workflow

Upload Images – Upload two multispectral satellite images

Preprocessing – Normalize and prepare bands for analysis

Index Calculation – NDVI, NDWI, NDBI

Classification – Assign land cover categories

Change Detection – Compare two images and highlight differences

Visualization – RGB composites, Change Maps, Change Matrix, Graphs

📊 Outputs

Land Cover Percentages for each category

Change Matrix showing differences between years

Change Map (White = Change, Black = No Change)

Scatter Plot comparing land cover percentages

## 🛠️ Installation
Install the required libraries before running:

```bash
pip install rasterio earthpy numpy matplotlib pandas
