# RemoteSensingNDVI

## Overview
This project explores **remote sensing data** to analyze vegetation using **Sentinel-2 satellite imagery**. It focuses on computing the **Normalized Difference Vegetation Index (NDVI)** and visualizing vegetation dynamics over time. The project also includes orthophotos for comparison with Sentinel-2 images.

## Dataset
- **Name:** IMAsatADTP  
- **Type:** Multispectral satellite imagery (Sentinel-2) and orthophotos  
- **Bands used:** B2, B3, B4, B8  
- **Coverage:** Urban areas, including Paris (Ile-de-France)  
- **Availability:** Provided for this lab   

## Files
- `RemoteSensing.ipynb` – Jupyter notebook containing all analyses, visualizations, and NDVI computations  
- `RS_Report` – Lab report documenting methodology, results, and discussions  

## Features
- Load and visualize Sentinel-2 multispectral images  
- Compute NDVI maps and average NDVI values  
- Compare Sentinel-2 imagery with high-resolution orthophotos  
- Track vegetation changes over time using NDVI time series  

## Requirements
- Python 3.x  
- Libraries: `rasterio`, `fiona`, `numpy`, `matplotlib`  

## Usage
1. Clone the repository:  
```bash
git clone https://github.com/HadiaAmjad4/RemoteSensingNDVI.git
