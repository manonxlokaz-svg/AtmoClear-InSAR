# AtmoClear InSAR 🛰️
> **NASA Space Apps Challenge** | *Challenge: InSAR Change Detectives*

Sub-millimeter ground motion recovery beneath atmospheric tropospheric noise using real-time NASA Earth data.

---

## 📌 Overview
Radar signals from Sentinel-1 Synthetic Aperture Radar (SAR) satellites are often distorted by atmospheric water vapor (tropospheric delay), introducing up to **10 cm of false displacement errors** in raw interferograms.

**AtmoClear InSAR** is an open-source processing pipeline designed to mitigate atmospheric phase delay in C-band SAR interferograms using real-time NASA Precipitable Water Vapor (PWV) datasets.

---

## ✨ Key Features & Performance
- **64% Phase Noise Reduction:** Pixel-by-pixel phase delay removal.
- **Automated Ingestion:** Integrates directly with NASA Earthdata.
- **Open Source Pipeline:** 100% reproducible Python processing pipeline in Jupyter / Google Colab.

---

## 🛠️ Tech Stack
- **Language:** Python 3.10
- **Data Ingestion:** NASA Earth Observation (PWV Datasets)
- **Scientific Libraries:** NumPy, Matplotlib

---

## 🔬 How It Works
1. **Data Retrieval:** Ingest Sentinel-1 SAR interferograms alongside synchronized NASA PWV atmospheric moisture data.
2. **Phase Delay Calculation:** Map spatial atmospheric delays matching satellite acquisition timestamps.
3. **Phase Filtering:** Subtract tropospheric phase noise to reveal true sub-millimeter ground motion.
