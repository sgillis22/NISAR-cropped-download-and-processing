# NISAR Data Download & Processing Notebooks

A collection of Python notebooks and utilities for downloading, cropping, and processing **NASA–ISRO NISAR** radar products.

**Author:** Seamus Gillis  
Cornell University  
skg72@cornell.edu

**NOTE:** Many of these scripts are still being edited and revised regularly and may not work exactly as intended. Any known errors or limited functionality may be listed within the notebooks. Regions that overlie multiple tracks or cover the interesction of multiple tracks are know to cause issue in data processing, this is still being worked on.

---

## Overview

This repository provides a practical workflow for working with NISAR GSLC and GUNW datasets, including:

- Automated granule discovery and download  
- Spatial and temporal filtering  
- Cropping to user‑defined areas of interest  
- Creating interferograms and amplitude‑based diagnostics  

For any dowload scripts, they will require your NASA earthdata search credentials in a .netrc, in the following format:

machine urs.earthdata.nasa.gov  
login your_login  
password your_password 

Given the release cycle of NISAR data, the scripts will download as much data as your account has access to, and as NISAR data release and calibration develops, scripts may require adjustment and further development.

---

## Repository Contents

### **GSLC_Download**
Tools for searching, filtering, and downloading **NISAR GSLC** granules.  
Supports:

- Date‑range filtering  
- Polarization selection  
- AOI cropping using GDAL  
- Saving georeferenced TIFFs for downstream analysis

### **GUNW_Download**

**Not neccessarily functional, under development**
Tools for searching, filtering, and downloading **NISAR GUNW** granules.  
Supports:

- Date‑range filtering  
- Polarization selection  
- AOI cropping using GDAL  
- Saving georeferenced TIFFs for downstream analysis
  
### **Data_Display_scripts**
Scripts for generating visual diagnostics from GSLC data, including:

- Raw amplitude images  
- Amplitude ratios  
- Wrapped and unwrapped interferograms  
- Export to PNG and GeoTIFF formats  


---

**Seamus Gillis**  
Cornell University  
skg72@cornell.edu
