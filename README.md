# 🌊 Enhancing Water Safety with an AI-Powered Quality Prediction System
**Project:** AI-based Water Quality Prediction using Satellite Imagery (Sentinel-2 + Google Earth Engine)  
**Author:** Sparsh Saini  
**Notebook:** `/mnt/data/Water_quality.ipynb` *(replace with GitHub link after uploading)*

---

## 🚀 Project Overview
This project develops an **AI-powered system** to predict critical **water quality indicators** such as **turbidity** and **chlorophyll** concentration using **satellite imagery from Sentinel-2**. By combining **Google Earth Engine (GEE)** for remote sensing and **machine learning models (Random Forest)** for prediction, the system provides a scalable, cost-effective solution for water safety monitoring, especially for lakes, reservoirs, and rivers.

A geo-visual dashboard is included to help authorities visualize trends and take informed decisions.

---

## 🔍 Key Features
- 🌐 **Remote Sensing:** Extraction of spectral bands, NDWI, chlorophyll indices, and turbidity proxies from Sentinel-2.
- 🛰️ **Google Earth Engine Integration:** Automated satellite data filtering, cloud masking, and feature preparation.
- 🤖 **Machine Learning Model:** Random Forest model trained on region-specific water quality data.
- 📈 **High Accuracy:** Achieves **over 90% precision** for turbidity and chlorophyll prediction.
- 🗺️ **Interactive Dashboard:** Visualizes water quality for multiple locations with trend charts and color-coded quality levels.
- ⚡ **Scalable Pipeline:** Designed for large-scale monitoring and periodic updates.

---

## 📊 Dataset & Features
### **Source:**
- Sentinel-2 MSI imagery (10m resolution)
- Extracted via Google Earth Engine

### **Features used:**
- Bands: B2, B3, B4, B8, B11, B12  
- Indices:  
  - NDWI (Normalized Difference Water Index)  
  - Chlorophyll-a Index  
  - Water Surface Reflectance  
- Additional engineered variables for turbidity estimation

---

## 🧠 Model
### **Algorithm:**
- **Random Forest Regressor**

### **Why Random Forest?**
- Performs well on high-dimensional remote sensing data  
- Robust to noise, cloud cover, spectral variation  
- Handles nonlinear relationships between reflectance and water quality metrics

### **Performance:**
- **Precision:** > 90%  
- **R² Score:** High for both turbidity and chlorophyll prediction  
- **Low RMSE** on regional datasets  

---


