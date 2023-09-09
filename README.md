# Lāhainā Fire Analysis
An investigation of how landcover change, particularly in the extent of agricultural lands, has been associated with increases in burned area from wildfires in Hawaiʻi. This analysis quantifies the extent to which non-native vegetation that dominates unmanaged colonial pasture and croplands have contributed increases in burned area over the past 24 years. 

Datasets include:
1. Area used for pasture, sugarcane, pineapple, total croplands in Hawaiʻi since 1898. Data columns include:
   Year: Year of the observation
   Crop: The agricultural land use
   Hectares: The area of that agricultural land use in hectares

2. Annual burned area in Hawaiʻi from 1904-2022. Data columns include:
   Year: Year of the observation
   BurnedHectares: The total area burned in wildfires that year in hectares
   
3. Burned area from large (mosly >20 ha) wildfires that occurred from 1999-2022 associated with former pasture, sugarcane, or pineapple land across all of Hawaiʻi. Data columns include:
   Year: Year of the observation
   LandCover: The former agricultural land use. Either pasture, sugarcane, or pineapple. "Other" indicates that the fire burned area did not overlap with any of these major historic agricultural land uses
   BurnedHectares: The total area burned in wildfires that year in hectares

4. Burned area from large (mosly >20 ha) wildfires that occurred from 1999-2022 associated with former pasture, sugarcane, or pineapple land in West Maui (including Lāhainā and Kāʻanapali). Data columns include:
   Year: Year of the observation
   LandCover: The former agricultural land use. Either pasture, sugarcane, or pineapple. "Other" indicates that the fire burned area did not overlap with any of these major historic agricultural land uses
   BurnedHectares: The total area burned in wildfires that year in hectares
   
5. Monthly rainfall in West Maui from January 1999 through July 2023. Data columns include:
   YearMonth: The date of the observation for cumulative rainfall in a given month in a given year
   Rain_mm: The observed total rainfall (mm) in a given month in a given year
   Rain_mm_1yr: The 12-month rolling average of rainfall at any given point in time

Code is provided to reproduce the results from the analysis.
