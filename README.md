This repository contains the code used in the study:

**"Biophysical and sociodemographic determinants of green infrastructure (GI) spatial distribution in Gdańsk, Poland"**

## 📄 Overview

This project investigates how biophysical, socio-demographic, and environmental factors influence the spatial distribution of green infrastructure (GI) in Gdańsk, Poland.

The analysis is conducted using a 1 km grid-based framework and integrates spatial statistics, econometric modelling, and GIS-based analysis.

---

##  Methods Implemented

The workflow includes:
- Data preparation
- Normalization, Correlation and partial correlation analysis
  
- Spatial autocorrelation analysis  
  - Global Moran’s I  
  - Local Moran’s I (LISA)

- Global regression models  
  - Ordinary Least Squares (OLS)  
  - Weighted Least Squares (WLS)  
  - Generalized Least Squares (GLS)

- Spatial econometric models  
  - Spatial Lag Model (SLM)  
  - Spatial Error Model (SEM)

- Geographically Weighted Regression (GWR)  
  - Adaptive bandwidth selection  
  - Local coefficient and t-value mapping  

- GI priority mapping  
  - Percentile-based classification  
  - Identification of high-priority intervention zones  

---

##  Requirements

The code is implemented in Python (tested in Google Colab).

## Required libraries:
geopandas
numpy
pandas
matplotlib
pysal
mgwr
scikit-learn
and more depending upon requirement

## Install using:

pip install geopandas pysal mgwr scikit-learn matplotlib

##  How to Run

1. Open the notebook:

   `gi_spatial_analysis_gdansk.ipynb`

2. Run all cells sequentially

3. Ensure input datasets are available (see Data section below)


##  Data Availability

All datasets used in this study are publicly available:

- Geoportal Poland (DEM, BDOT10k):  
  https://mapy.geoportal.gov.pl  

- Copernicus Land Monitoring Service (Urban Atlas):  
  https://land.copernicus.eu  

- Google Earth Engine (Landsat, Sentinel):  
  https://earthengine.google.com  

- GIOŚ (air pollution data):  
  https://powietrze.gios.gov.pl  

- Gdańskie Wody (hydrological data):  
  https://www.gdanskiewody.pl  

- Statistics Poland (GUS):  
  https://stat.gov.pl  



##  Reproducibility

All results (figures, tables, and spatial outputs) presented in the manuscript can be reproduced by running the notebook sequentially.

The workflow follows a structured pipeline:

Data preparation → Spatial analysis → Regression modelling → GWR → Priority mapping

---

##  Code Availability

The code associated with this repository is archived at:

👉 https://doi.org/10.5281/zenodo.19183653

---

## Notes

- The notebook has been cleaned for reproducibility and clarity  
- Intermediate/debug outputs have been removed  
- The analysis is designed for research and academic use  

---

##  Contact

For questions related to this repository or the study, please contact the authors.
