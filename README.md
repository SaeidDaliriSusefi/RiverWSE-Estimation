# 🌍 River Water Surface Elevation Analysis using ICESat-2 Altimetry Data

This repository provides a complete Python-based tool for analyzing river cross-sections using ICESat-2 ATL03 photon height data. The main objective is to estimate the Water Surface Elevation (WSE) and river width along a selected cross-section by applying robust filtering, statistical modeling, and visual interpretation techniques.

## 📸 Example Outputs

![image alt](https://github.com/SaeidDaliriSusefi/RiverWSE-Estimation/blob/e3f9595084c16ef02e258e8cd3c0a8841ba64bf1/Images/River__.png)

## Features
📐 Automatic orientation detection: Determines whether the cross-section is aligned north–south or east–west.

🧹 Noise filtering: Applies Hampel filtering followed by median filtering to clean photon height data.

📏 Distance computation: Calculates distances along the cross-section using lat/lon coordinates.

📊 Statistical water surface detection: Uses Kernel Density Estimation (KDE) to identify the most probable water surface height.

📌 River width estimation: Computes river width using 1st and 99th percentiles of detected water surface points.

