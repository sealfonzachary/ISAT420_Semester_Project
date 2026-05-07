<center>
<h1>ISAT 420 Semester Project - Ghost Forest Formation</h1>
</center>
<br>
<center>
<img src="OtherMaterials/JMU_Seal.svg" alt="JMU Logo" width="300">
</center>

## Project Overview

This repository contains the code, data, documentation, and final project report for an ISAT 420 semester project focused on potential ghost forest expansion in the Chesapeake Bay region.

The project examines whether areas of potential forest-to-wetland transition are spatially associated with relative sea level rise and salinity trends. Potential ghost forest transition pixels were identified using National Land Cover Database (NLCD) land-cover change between 2001 and 2021. These transition pixels were then compared with NOAA tide gauge relative sea level rise trends and Chesapeake Bay Program salinity monitoring trends.

The final analysis uses NOAA tide gauge stations as spatial anchor points. A 15-kilometer buffer was created around each tide gauge station, and the project summarized:

- Relative sea level rise rate at each tide gauge station
- Average salinity trend of nearby monitoring stations
- Number of potential ghost forest transition pixels within the buffer
- Number of salinity stations within the buffer
  
<center>
<img src="OtherMaterials/Spatial_Correlation_RSLR_Salinity_GhostForest_Map.png" width="500">
</center>

This project is exploratory. The NLCD forest-to-wetland transition method does not confirm that every selected pixel is a true ghost forest. Instead, it provides a land-cover-based proxy for possible ghost forest expansion.

---

## Repository Purpose

The purpose of this repository is to provide a reproducible record of the semester project workflow. It includes:

- Jupyter notebooks used to download, clean, process, and analyze the data
- Raw and processed data files used in the analysis
- Documentation explaining the data sources and acquisition process
- A computational environment file for reproducing the Python environment
- A final project report notebook containing the integrated analysis

---

## Repository Structure

```
ISAT420_Semester_Project/
├── README.md
├── ISAT_420.yml
├── ProjectReport.ipynb
├── Code/
│   ├── NLCDLandUse.ipynb
│   ├── SalinityStations.ipynb
│   └── TidalStations.ipynb
├── Data/
│   ├── aiohttp_cache.sqlite
│   ├── SalinityMain.csv
│   ├── SalinityTributary.csv
│   ├── RSLR_Trend_Summary.csv
│   ├── Salinity_Trend_Summary.csv
│   └── RSLR_Salinity_GhostForest_Comparison.csv
├── Documentation/
│   └── DataAcquisition.md
└── OtherMaterials/
    └── JMU_Seal.svg
```

---

## Acknowledgements

We would like to congratulate Dr. Tobias Gerken on his tenure at James Madison University and thank him for his help, guidance, and support throughout the semester. His feedback and instruction were valuable in developing this project and improving the final analysis.

---

## Authors

William DeSimone, Zachary Sealfon, Kian Soltani, Melanie Wartluft