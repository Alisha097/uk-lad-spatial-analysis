# Spatial Analysis of UK Local Authority Districts (LADs)

## Project Overview
This project performs a spatial analysis of the **UK Local Authority Districts (LADs)**, linking them to **ITL1 regions** (12 major regions of the UK). The goal is to understand the geographic characteristics, size, shape, and distribution of LADs, and classify them into **urban or rural** proxies based on median area.

The analysis includes:
- Spatial join of LADs with ITL1 regions
- Feature engineering: area, perimeter, compactness
- Urban/Rural classification based on median LAD area
- Descriptive statistics and visualisations

---

## Data Sources
1. **UK LADs**: Local Authority District boundaries (May 2024) - ['https://geoportal.statistics.gov.uk/datasets/ons::local-authority-districts-may-2024-boundaries-uk-bgc-2/about']
2. **ITL1 Regions**: UK regions (January 2025) - ['https://geoportal.statistics.gov.uk/datasets/international-territorial-levels-level-1-january-2025-names-and-codes-in-the-uk/about']

Both datasets are in **shapefile format** and processed using **GeoPandas**.

---

## Dataset Overview
1. **UK LADs**: Local Authority District boundaries (May 2024)
    Columns:
  - LAD24CD: LAD code
  - LAD24NM: LAD name
  - BNG_E/BNG_N: Easting/Northing coordinates (British National Grid)
  - LAT/LON: Latitude/Longitude
  - GlobalID: Unique Identifier
  - geometry
   
2. **ITL1 Regions**: UK regions (January 2025)
    Columns:
  - ITL125CD: Region code
  - ITL125NM: Region name
  - BNG_E/BNG_N: Easting/Northing coordinates (British National Grid)
  - LAT/LON: Latitude/Longitude
  - GlobalID: Unique Identifier
  - geometry



