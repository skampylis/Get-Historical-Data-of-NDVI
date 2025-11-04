# 🌿 **Get Historical Data of NDVI**

## **📘 Description**

This project provides a **Python-based workflow** for retrieving, processing, and visualizing **historical NDVI (Normalized Difference Vegetation Index)** data using remote sensing APIs. It enables users to extract **time-series vegetation data** for defined geographic areas and time ranges, supporting long-term **environmental monitoring**, **agricultural analysis**, and **land use studies**.

The workflow automates NDVI collection from **Google Earth Engine (GEE)** and similar data sources, applies filtering for cloud coverage and scaling, and outputs both raw and aggregated datasets ready for further analysis or visualization.

---

## **🚀 Project Overview**

* **NDVI Extraction:** Retrieves historical NDVI data for specific coordinates, shapefiles, or bounding boxes.
* **Time-Series Analysis:** Computes NDVI values across multiple years to detect seasonal or long-term vegetation changes.
* **Data Cleaning & Filtering:** Applies cloud masking, normalization, and smoothing for cleaner datasets.
* **Visualization:** Generates NDVI plots and interactive charts to highlight vegetation trends.
* **Automation:** Streamlined code suitable for integration into larger geospatial data pipelines.

---

## **🧠 Key Features**

* 🌎 **Satellite-based Data Retrieval:** Utilizes Sentinel-2 or MODIS datasets via **Google Earth Engine**.
* 🧮 **Automated NDVI Computation:** Calculates NDVI using `(NIR - RED) / (NIR + RED)` for each scene.
* 📅 **Historical Tracking:** Supports analysis across years or seasons for trend evaluation.
* 📊 **Interactive Visualization:** Plots NDVI time-series using `matplotlib` or `plotly`.
* 💾 **Export Options:** Outputs processed NDVI data as `.csv`, `.json`, or plotted figures for reports and dashboards.

---

## **⚙️ Technical Details**

* **Language:** Python
* **Libraries:** `geemap`, `ee`, `pandas`, `matplotlib`, `geopandas`, `datetime`, `os`, `json`
* **Data Sources:** Sentinel-2 (MSI), MODIS Vegetation Indices, or other GEE datasets
* **Outputs:**

  * Time-series NDVI datasets (`.csv`)
  * NDVI visualization plots (`.png`, `.html`)
  * Summary statistics and metadata

---

## **📂 Code Structure**

* **`Get_Historical_Data_of_NDVI.ipynb`** – Main notebook with data retrieval, visualization, and export workflow.
* **`get_historical_data_of_ndvi.py`** – Core Python script for automated NDVI extraction and processing.
* **`/data`** – (Optional) Folder for input coordinates or shapefiles.
* **`/outputs`** – Stores NDVI plots and exported CSV results.

---

## **🧩 How It Works**

1. **Define Region:** Specify your area of interest (coordinates, GeoJSON, or shapefile).
2. **Select Date Range:** Input the start and end dates for NDVI extraction.
3. **Run the Script/Notebook:** Fetch NDVI data from Earth Engine and compute values.
4. **Analyze & Visualize:** Explore NDVI evolution across time using time-series plots and summary statistics.

---

## **📈 Example Output**

* NDVI time-series plot showing vegetation dynamics.
* CSV file with NDVI values per date and region.
* Visual overlay maps highlighting vegetation intensity changes.

---

## **🏷️ Tags**

`NDVI` `Google Earth Engine` `Remote Sensing` `Python` `Geospatial Analysis` `Satellite Imagery` `Environmental Monitoring` `Time-Series`

---

## **🌟 Concept**

*“A geospatial automation tool for tracking vegetation health over time using NDVI and satellite imagery — bridging environmental data science with machine learning and Earth observation.”*
