# 🌊 AI-based Water Body Detection for inundation Area
This repository contains codes and data related to a research project focused on water body detection in ungauged areas using Earth observation satellites (primarily SAR) and AI.

---

## 💾 Datasets
### 🛰️ ESA Sentinel-1
ESA's Sentinel-1 mission provides continuous, all-weather, and day-and-night radar imagery of Earth's surface through its Synthetic Aperture Radar (SAR) instrument. The primary reason for using this data in water body detection is SAR's unique capability to penetrate cloud cover and darkness. This is crucial for monitoring floods and other dynamic water changes in near real-time, as optical satellites (which rely on visible light) are often obstructed by clouds during heavy rain or storms. Additionally, water bodies appear very dark in SAR imagery due to specular reflection, making them highly distinguishable from surrounding land features.

The data used in this project was obtained from the Alaska Satellite Facility (ASF) DAAC via its bulk download script, allowing for efficient acquisition of large, time-series datasets.

> **Data Access**

<a href="https://search.asf.alaska.edu/">
  <img src="https://asf.alaska.edu/wp-content/uploads/2022/08/asf-logo-blue-nav.png" alt="[Go to ASF DAAC]" width="30%">
</a>

---

### 🗺️ Copernicus Emergency Management Service
The Copernicus Emergency Management Service (EMS) provides geospatial information derived from satellite imagery for rapid mapping and monitoring of disasters. This service generates detailed flood delineation maps in vector format, which are used by emergency response organizations worldwide.

In this research, these high-quality, pre-processed flood maps were utilized as ground truth (label) data to validate the accuracy of the water body detection model trained with Sentinel-1 SAR imagery. The EMS dataset's operational focus and temporal alignment with flood events make it an ideal source for verifying the performance of our AI model.

> **Data Access**

<a href="https://mapping.emergency.copernicus.eu/activations/">
  <img src="https://emergency.copernicus.eu/static/images/cems-logo-ext.png" alt="[Go to Copernicus EMS]" width="30%">
</a>

---

Developed by: [Seongjun Lee](mailto:seongjunlee4473@gmail.com?subject=Questions%20for%20GitHub%20projects) @ Sep 2025
