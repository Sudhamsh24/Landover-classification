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

## 🛠️ Installation
Install the required libraries before running:

```bash
pip install rasterio earthpy numpy matplotlib pandas
