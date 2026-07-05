## Automated Land Surface Temperature (LST) Mapping and Spatial Analytics Pipeline

### Location Map: West Bengal
`landsat-9` `landsat-8` `geospatial-analysis` `remote-sensing` `land-surface-temperature` `rasterio` `python` `spatial-analytics` `eda` `folium` `pydeck` `gis` `morans-i` `satellite-imagery` `wgs84`

This project delivers an end-to-end geospatial analytics pipeline built in Python to process, calibrate, and visualize satellite imagery from the Landsat 8/9 missions. By converting raw Digital Numbers (DN) into calibrated Celsius values, the workflow successfully maps Land Surface Temperature (LST) across target scenes. It features automated geographic reprojection from native UTM coordinates to WGS84, exploratory data profiling (including density, anomaly, and cross-sectional transect checks), and spatial autocorrelation analysis using Local Moran's I. The final outputs include highly localized statistical summaries and interactive 2D (Folium) and 3D (Pydeck) thermal distribution map overlays.


| Metric | Value |
| :--- | :--- |
| **Total Valid Pixels Processed** | 40,509,006 |
| **Minimum Temperature** | -2.12°C |
| **Maximum Temperature** | 68.39°C |
| **Mean Temperature** | 37.33°C |
| **Median Temperature** | 37.58°C |
| **Standard Deviation** | 3.25°C |

## Map Overview 
<img width="816" height="575" alt="Screenshot 2026-07-05 192211" src="https://github.com/user-attachments/assets/20530824-f1ff-4b8b-9cfb-cdb312cb4b7c" />

## Cross-Sectional LST Transect (Spatial Profiles)

<img width="671" height="207" alt="image" src="https://github.com/user-attachments/assets/d6b9da2f-6bd6-44ba-9e3c-b756150b6942" />

| | |
| :---: | :---: |
| <img width="400" alt="Spatial Distribution of LST" src="https://github.com/user-attachments/assets/f9a4dee1-29fd-4a62-9217-63a5900a5677" /> | <img width="400" alt="Temperature Profile Density" src="https://github.com/user-attachments/assets/8bfbbe11-152c-4e6b-9e26-2e13ead924d9" /> |
| <img width="400" alt="LST Boxplot Structure" src="https://github.com/user-attachments/assets/6c61a570-b701-4b7d-abbd-a8801a1a4634" /> | <img width="400" alt="Thermal Profiles Transect" src="https://github.com/user-attachments/assets/7d95a638-bb55-47f7-b44c-7becf48feeef" /> |


# Data Set Link 

Link ->  https://www.kaggle.com/datasets/sayaksamanta/landset-lc08-l2sp-139044-20260601-20260612-02-t1

Colleted from USGS -- United States Geological Survey | geological organization ...USGS stands for the United States Geological Survey. 
It is a major scientific agency within the U.S. Department of the Interior. The agency specializes in conducting research on biology, geography, geology, and hydrology, while also serving as a leading provider of topographical mapping and natural disaster monitoring. You can explore their research and resources on the U.S. Geological Survey official website

https://earthexplorer.usgs.gov/



