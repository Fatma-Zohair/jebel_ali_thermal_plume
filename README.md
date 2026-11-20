# jebel_ali_thermal_plume
environmental data analysis capston project
# Thermal Footprint of the Jebel Ali Power and Desalination Complex (Dubai)

# Project Description

The Jebel Ali Power and Desalination Complex discharges heated water into the Arabian Gulf. Because the Gulf is semi-enclosed and exchanges water slowly with the open ocean, this heated water may not disperse quickly, which could create a detectable local warm-water area (thermal plume). This project uses high-resolution satellite imagery (Landsat 8/9) to test whether such a plume can be detected, and to measure its size, shape and seasonal changes between 2022 and 2025, within a 15 km coastal radius of the complex.

# Research Questions
What is the spatial extent (km²) of the thermal plume exceeding the ambient baseline by more than 2°C, and how sensitive is this measurement to threshold variations?
How do the spatial footprint and magnitude of the thermal anomaly change seasonally (summer vs. winter)?
Is the Sea Surface Temperature (SST) difference between the discharge zone and matched control zones statistically significant when adjusting for wind and tidal covariates?

# Datasets
                      Dataset | Description | Source |
1. Landsat 8/9 thermal bands | Sea surface temperature (30 m), quality flags and dates, 2022–2025 | USGS |
2.  Hourly wind observations | 	Wind direction, speed and gust from Al Maktoum International Airport (OMDW), the closest weather station to the complex (~20 km), 2022–2025, UTC | Iowa Environmental Mesonet – ASOS/METAR |

# Tools
R (readr, dplyr, tidyr), run in Google Colab
