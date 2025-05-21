# Global Topography Analysis (Updated May 28, 2024)

This Jupyter Notebook (`Topography_v2_Global.ipynb`) provides a data-driven analysis and visualization of global topography using geospatial datasets. It leverages Python's geospatial and visualization libraries to explore, process, and present elevation data at a global scale.

---

##  Project Overview

The goal of this project is to:
- Load and process global elevation (topography) datasets.
- Perform exploratory data analysis (EDA) on topographic data.
- Generate insightful visualizations including maps, histograms, and elevation distribution plots.
- Enable scalable, reproducible geospatial analysis using open-source Python tools.

---

##  Tools & Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `geopandas`
- `rasterio`
- `xarray`
- `cartopy`
- `seaborn`
- `matplotlib.pyplot`

---

## Key Features

- Load and read global raster datasets (e.g., DEM data).
- Reproject and clip raster layers to match global boundaries.
- Visualize elevation with color maps and overlays.
- Compute summary statistics on elevation values.
- Handle large-scale geospatial datasets efficiently.

---

## Example Visualizations

- Global topography maps using custom colormaps
- Elevation histograms and distribution plots
- Comparative views of elevation across regions

---

## How to Run

1. Clone this repository or download the notebook.
2. Ensure you have the required dependencies installed:
   ```bash
   pip install numpy pandas matplotlib geopandas rasterio xarray cartopy seaborn
