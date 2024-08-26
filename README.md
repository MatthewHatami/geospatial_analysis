# Climate Data Analysis Project

## Overview
This repository contains different folders dedicated to analyzing climate and geospatial data. 
Below you can find a short summary and structure of each folder in this repository.


## Repository Structure

### 1. EU Precipitation Analysis
- **Folder:** `eu_precipitation_analysis`
- **Description:** This folder contains notebooks that analyze precipitation data across the European Union from 2013 to 2023. The analysis includes processing raw data, generating visualizations, and interpreting trends in precipitation across different EU regions.

  - **Notebook 1:** `precipitation_in_eu_2013_2023.ipynb`
    - **Description:** Focuses on detailed analysis of precipitation trends over the past decade in the EU, offering insights into regional variations and changes over time.

### 2. World Temperature Analysis
- **Folder:** `world_temperature_analysis`
- **Description:** This folder contains notebooks that analyze global temperature data. The analysis includes evaluating temperature trends across various regions of the world, identifying patterns, and understanding long-term changes in global temperatures.

  - **Notebook 1:** `data_handling.ipynb`
    - **Description:** Covers the methods used to handle and preprocess global temperature datasets. This includes data cleaning, transformation, and preparation for further analysis.

  - **Notebook 2:** `data_analysis.ipynb`
    - **Description:** Provides statistical and exploratory analysis of global temperature data, exploring correlations, trends, and regional temperature variations.

## Requirements
To run the notebooks, you will need the following Python packages:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `xarray`
- `netCDF4`
- `geopandas`
- `rasterio`

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib seaborn xarray netCDF4 geopandas rasterio
