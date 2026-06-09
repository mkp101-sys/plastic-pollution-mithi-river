# Plastic Pollution Detection in the Mithi River Using Sentinel-2 and Google Earth Engine

## Overview

This project investigates floating plastic pollution in the Mithi River, Mumbai, using Sentinel-2 satellite imagery and Google Earth Engine (GEE). The study applies the Floating Debris Index (FDI) to identify plastic-contaminated regions and compares pollution patterns between 2017 and 2023.

## Objectives

* Detect floating plastic debris in the Mithi River.
* Calculate the Floating Debris Index (FDI).
* Generate plastic pollution maps.
* Compare pollution conditions between 2017 and 2023.
* Analyze changes in plastic distribution over time.

## Study Area

The study focuses on the Mithi River, Mumbai, Maharashtra, India. The river flows through densely populated urban and industrial areas and is significantly affected by anthropogenic waste and pollution.

## Data Used

### Satellite Data

* Sentinel-2 Surface Reflectance (COPERNICUS/S2_SR)

### Platform

* Google Earth Engine (GEE)

### Spatial Resolution

* 10 m

## Methodology

1. Define Area of Interest (AOI)
2. Import Sentinel-2 imagery
3. Apply cloud masking
4. Generate water mask
5. Calculate Floating Debris Index (FDI)
6. Perform threshold-based plastic classification
7. Generate plastic pollution maps
8. Compare results between 2017 and 2023

## Workflow

![Workflow](images/workflow.png)

## Results

### Plastic Distribution Analysis

The analysis was performed for multiple years to identify spatial and temporal variations in floating plastic pollution.

### Key Findings

* Mean FDI increased between 2017 and 2023.
* Large floating plastic patches decreased slightly.
* Smaller and more dispersed plastic debris increased.
* Several pollution hotspots remained persistent across years.

## Repository Structure

```text
Plastic-Pollution-Mithi-River/
│
├── README.md
├── LICENSE
│
├── report/
│   └── EO PROJECT MK.pdf
│
├── gee_code/
│   └── gee_script_screenshot.png
│
├── images/
│   ├── study_area.png
│   ├── workflow.png
│   ├── plastic_2017.png
│   ├── plastic_2023.png
│   └── change_detection.png
```

## Technologies Used

* Google Earth Engine
* Remote Sensing
* Sentinel-2
* GIS
* Earth Observation
* Environmental Monitoring

## Future Improvements

* Integration of machine learning for plastic classification.
* Multi-season monitoring.
* Sentinel-1 and Sentinel-2 data fusion.
* Automated plastic pollution monitoring dashboard.

## Author

**Maharshi K. Patel**

M.Sc. Earth Observation

Dhirubhai Ambani University

## License

This project is released under the MIT License.
