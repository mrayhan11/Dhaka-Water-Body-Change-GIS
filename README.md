# Dhaka Water Body Change GIS

GIS-based assessment of temporal changes in surface water bodies in Dhaka City, Bangladesh, using Landsat satellite imagery, manual digitization, ArcGIS spatial analysis, and Microsoft Excel.

This repository documents the geospatial workflow used in the study:

**Rayhan, M., Mobarrat, M. M., Nujhat, M., Paul, R. K., & Amin, M. K. (2025).  
Assessment of the temporal variations of surface water bodies in Dhaka City using Landsat imagery.  
Discover Geoscience, 3, 91.**

DOI: https://doi.org/10.1007/s44288-025-00195-6

---

## Overview

Rapid urbanization has significantly changed the hydrological landscape of Dhaka City.

This study mapped and quantified changes in surface water bodies within the Dhaka Metropolitan Region between **2004 and 2021**.

The analysis focused on urban surface water features including:

- Lakes
- Canals
- Wetlands
- Other visible surface water bodies

The main workflow combined Landsat satellite imagery with manual GIS digitization to identify and quantify changes in water-body area.

---

## Study Area

The study covers the **Dhaka Metropolitan Region, Bangladesh**.

Approximate geographic extent:

- Latitude: 23.40°N – 23.90°N
- Longitude: 90.20°E – 90.50°E

Total study area:

**317.20 km²**

---

## Data

### Landsat Imagery

Satellite images were obtained from the **USGS Earth Explorer** platform.

Two main periods were analyzed:

| Year | Image Date | Purpose |
|---|---|---|
| 2004 | November 13, 2004 | Historical water-body mapping |
| 2021 | February 14, 2021 | Recent water-body mapping |

Landsat imagery has a spatial resolution of approximately **30 m**.

Dry-season imagery was selected to reduce cloud interference and improve comparison between the two periods.

---

## Methodology

The main analysis was conducted using **ArcGIS**.

### 1. Satellite Image Preparation

Landsat imagery was prepared using standard image-processing procedures, including:

- Radiometric calibration
- Atmospheric correction
- Cloud masking
- Geometric correction

### 2. Water Body Identification

Water bodies were identified using:

- Short-Wave Infrared (SWIR) bands
- Near-Infrared (NIR) band
- True-color imagery
- False-color imagery
- Visual interpretation

These combinations helped distinguish water surfaces from surrounding urban land.

### 3. Manual Digitization

Visible water bodies were manually digitized as polygons in ArcGIS.

Manual digitization was selected because complex urban environments can create spectral confusion between:

- Water
- Urban shadows
- Buildings
- Wet soil
- Other dark surfaces

Manual interpretation allowed water-body boundaries to be refined using the surrounding geographic context.

### 4. Area Calculation

The area of each digitized water-body polygon was calculated in ArcGIS.

Total water-body area was then calculated for:

- 2004
- 2021

### 5. Temporal Change Analysis

The digitized water-body layers from 2004 and 2021 were compared to identify:

- Water-body loss
- Changes in spatial distribution
- Fragmentation
- Changes in water-body connectivity
- Areas experiencing substantial water-body reduction

### 6. Excel Analysis

Microsoft Excel was used for additional statistical analysis and visualization, including:

- Water-body area comparison
- Percentage change
- Trend visualization
- Rainfall comparison
- Preparation of charts and summary tables

---

## Workflow

```text
Landsat Satellite Images
          │
          ▼
Image Pre-processing
          │
          ▼
SWIR / NIR / Visual Interpretation
          │
          ▼
Water Body Identification
          │
          ▼
Manual Polygon Digitization in ArcGIS
          │
          ▼
Water Body Area Calculation
          │
          ▼
2004 vs 2021 Spatial Comparison
          │
          ▼
Excel Statistical Analysis
          │
          ▼
Maps, Figures and Temporal Change Assessment
