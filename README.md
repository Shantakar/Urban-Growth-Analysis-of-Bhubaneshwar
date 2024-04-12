
## Urban Growth Analysis of Bhubaneshwar
### Overview
This repository contains data, code, and analysis pertaining to the urbanization and climate study of Bhubaneswar, Odisha. The focus is on understanding the impacts of rapid urbanization on land use, land cover (LULC), and microclimate, particularly Urban Heat Islands (UHI).

### Study Objectives
1. **Land Use and Land Cover (LULC) Mapping**: Utilize Landsat satellite imagery to map LULC changes over the years (1993, 2003, 2013, 2023) using Google Earth Engine (GEE). Employ Random Forest classifier for accurate mapping and assess changes in urban areas.
   
2. **Temperature Analysis (LST)**: Calculate Land Surface Temperature (LST) using Landsat thermal bands to quantify UHI effects. Explore spatial variability using Urban Thermal Field Variance Index (UTFVI).

3. **Nighttime Lights (NTL) Analysis**: Evaluate changes in Nighttime Lights (NTL) using DMSP-OLS (1993, 2003) and VIIRS (2013, 2023) data to understand urbanization trends and human activity.

4. **Future Land Use Prediction**: Employ Cellular Automata modeling (MOLUSCE plugin in QGIS) based on historical LULC maps (1993-2023) and spatial variables (CBD, population, roads) to predict future (2033) LULC scenarios.

### Data Sources
1. **Landsat Imagery**: Landsat 5 TM (1993, 2003) and Landsat 8 TM (2013, 2023) data for LULC mapping and LST analysis.
   
2. **Global Human Settlement Layer (GHSL)**: Population surfaces (1993, 2003, 2013, 2023) for demographic analysis.

3. **Nighttime Lights (NTL)**:
   - DMSP OLS (1993, 2003) for historical NTL data.
   - VIIRS DNB (2013, 2023) for recent NTL data.

### Methodology
- **LULC Mapping**: Utilize Google Earth Engine (GEE) to process Landsat imagery, apply Random Forest classifier, and derive LULC maps.
  
- **Temperature Analysis**: Compute LST from Landsat thermal bands and calculate UHI and UTFVI indices to quantify thermal variability.

- **Nighttime Lights Analysis**: Process DMSP-OLS and VIIRS data to assess urbanization trends and nighttime activity.

- **Future Prediction**: Use Cellular Automata modeling with spatial variables to predict LULC changes up to 2033.


### Results
- **LULC Maps**: Generated maps depicting urbanization patterns from 1993 to 2023.
  
- **Temperature Analysis**: Visualizations and statistics on LST, UHI, and UTFVI trends.
  
- **Nighttime Lights Analysis**: Comparative analysis of NTL changes over the years.

- **Future Prediction**: Predicted LULC map for 2033 based on historical trends and spatial factors.

### Conclusion
This repository provides comprehensive insights into the urbanization dynamics of Bhubaneswar and its impact on the local climate. The analysis underscores the importance of sustainable urban planning to mitigate adverse effects and ensure the city's long-term resilience and livability.

Below are the GEE Code links for LULC classification for better convenience 
1993
https://code.earthengine.google.com/a6949f31849ec500a28645a857192b6f
2003
https://code.earthengine.google.com/db25a6f058973448fdd4434821482c25
2013
https://code.earthengine.google.com/66cde522f2bc9aef3627dad14c135524
2023
https://code.earthengine.google.com/b0032b19742442feb092faea502f36bd
Change Detection
https://code.earthengine.google.com/fa556154c3e3cb546e7a3309cfd0d53e

