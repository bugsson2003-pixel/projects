<p align="center">
<img style="max-width:100%;"
src="https://cdn2.picryl.com/photo/2011/07/02/summer-heatwave-in-spain-image-of-the-day-0280de-1024.jpg"
alt="Solar Panel"/>
</p>

---

# 🔥 Urban Heat Island
This project analyzed and predicted trends in the Urban Heat Island (UHI) effect in Gwangju, South Korea using optical satellite data and machine learning (ML) approaches.

This research was conducted with the support of a grant from the Gwangju Climate & Energy Agency's **`Small Research Grant Program`**.

---

## 💾 Datasets
### 🛰️ NASA Harmonized Landsat and Sentinel-2 (v2.0)
The Harmonized Landsat and Sentinel-2 (HLS) project, initiated by NASA, provides a powerful solution for Earth observation by combining data from the NASA Landsat-8/9 and ESA Sentinel-2 satellite missions.
The goal is to create a harmonized, or "sensor-agnostic," dataset of 30-meter resolution surface reflectance that can be used as if it were acquired by a single satellite **(Ju et al., 2025)**.

HLS processing applies the same algorithms to both Landsat and Sentinel-2 data to correct for atmospheric effects, normalize for view angle differences, and adjust for subtle spectral bandpass variations between the sensors **(Ju et al., 2025)**.

The result is an Analysis Ready Data (ARD) product that reduces the pre-processing burden for users. The HLS V2.0 dataset, completed in 2023, provides a global median of 66 cloud-free observations per year over land, significantly more than a single sensor could provide alone **(Ju et al., 2025)**.

> **Data Access**

<a href="https://search.earthdata.nasa.gov/search?q=HLS">
  <img src="https://www.earthdata.nasa.gov/themes/custom/project/hds_earthdata/nasa-earthdata-logo.png" alt="[Go to NASA EarthData]" width="30%">
</a>

---

### 🌡️ Temperature Data from Korea Meteorological Administration
The Korea Meteorological Administration (KMA) provides official and high-quality meteorological data, including historical and real-time temperature observations from its network of ground-based weather stations. This data is essential for accurate climate and weather analysis in South Korea.

In this project, the KMA's temperature data was utilized as ground truth (label) data to validate the accuracy of UHI prediction model. By comparing the temperature values predicted by our ML model with the actual, observed temperatures from KMA's stations, we were able to evaluate the model's performance and ensure its reliability for analyzing and forecasting UHI trends in Gwangju.

> **Data Access**

<a href="https://data.kma.go.kr/cmmn/main.do">
  <img src="https://data.kma.go.kr/resources/images/common/logo_top1.png" alt="[Go to KMA Open MET Data Portal]" width="15%">
</a>

---

Developed by: [Seongjun Lee](mailto:seongjunlee4473@gmail.com?subject=Questions%20for%20GitHub%20projects) & [Subin Kim](mailto:sbkim.phy@gmail.com?subject=Questions%20for%20GitHub%20projects) @ Jun 2024
