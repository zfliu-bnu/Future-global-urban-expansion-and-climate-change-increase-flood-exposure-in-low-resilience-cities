# Future-global-urban-expansion-and-climate-change-increase-flood-exposure-in-low-resilience-cities
Data availability. All the data created in this study are openly available and the supplementary data can be downloaded from OneDrive (https://1drv.ms/u/c/e3ea9f00428b094d/IQBiIqMevhGXRqJXsJy45LyKAWZnoLqG6lkCTaNajWMpdEs?e=kkIjYJ) or 师大云盘(https://pan.bnu.edu.cn/l/h1MhVo). Other data are available from the corresponding author upon reasonable request.

List of supplementary data

Script

• Python script for population-constrained ANN-CA allocation of future urban population (appendix_ann_ca_urban_population.py)

Data files

• Flood-exposure GeoTIFF raster files for the 2020 baseline and 2050 scenario combinations (Flood_Exp_tif; 100 .tif files).
• Raster naming rule for Flood_Exp_tif: <time>_<urban_population_data>_<floodplain>_<scenario>.tif. <time> is 2020 or 2050; <urban_population_data> is this-study, Chen, Li, He, or Gao; <floodplain> is CMIP6 or CMIP5 for 2020 baseline rasters and CMIP6-<GCM> or CMIP5-<GCM> for 2050 scenario rasters; <scenario> is historical, SSP2-RCP4.5, or SSP5-RCP8.5.
• Urban population data sources: This study = population-constrained ANN-CA allocation developed in this study using Liu et al. as the historical urban-expansion basis: Z. F. Liu, J. H. Ying, C. Y. He, Q. X. Huang, Q. X. Bai, X. H. Pan, Global Urban Expansion Simulation Dataset (1992-2050). J. Glob. Change Data Discov. 8, 90-97 (2024); Chen = Chen et al. (G. Chen et al., Global projections of future urban land expansion under shared socioeconomic pathways. Nat. Commun. 11, 537, 2020); Li = Li et al. (X. Li, Y. Zhou, M. I. Hejazi, M. A. Wise, C. R. Vernon, G. C. Iyer, W. Chen, Global urban growth between 1870 and 2100 from integrated high-resolution mapped data and urban dynamic modeling. Commun. Earth Environ. 2, 201, 2021); He = He et al. (W. He, X. Li, Y. Zhou, Z. Shi, G. Yu, T. Hu, Y. Wang, J. Huang, T. Bai, Z. Sun, X. Liu, P. Gong, Global urban fractional changes at a 1 km resolution throughout 2100 under eight scenarios of Shared Socioeconomic Pathways (SSPs) and Representative Concentration Pathways (RCPs). Earth Syst. Sci. Data 15, 3623-3639, 2023); Gao = Gao. (J. Gao, Downscaling global spatial population projections from 1/8-degree to 1-km grid cells, 2017).
• Floodplain and model labels: CMIP6 denotes the internally simulated CMIP6 flood-hazard maps using CMIP6-ACCESS-CM2, CMIP6-CanESM5, CMIP6-IPSL-CM6A-LR, and CMIP6-MIROC6; CMIP5 denotes the WRI Aqueduct Floods benchmark flood-hazard maps using CMIP5-GFDL-ESM2M, CMIP5-HadGEM2-ES, CMIP5-IPSL-CM5A-LR, CMIP5-MIROC-ESM-CHEM, and CMIP5-NorESM1-M.
• Scenario labels: historical = 2020 historical baseline; SSP2-RCP4.5 and SSP5-RCP8.5 are the two future socioeconomic-climate scenarios.
• File inventory: 100 rasters = 10 baseline rasters for 2020 (5 urban population datasets x 2 historical floodplain sources) + 90 scenario rasters for 2050 (5 urban population datasets x 9 GCM-based floodplain maps x 2 SSP-RCP pathways).
• Raster information: single-band GeoTIFF, Int32, LZW compressed; CRS = ESRI:54009 (World Mollweide equal-area); pixel size = 1,000 m x 1,000 m; raster size = 36,081 columns x 17,772 rows; NoData = 0. Cell values represent flood-exposed urban population counts in grid cells classified as floodplains.
• • Global city and urban-agglomeration boundary shapefile for cities with populations greater than 1 million (Global_cities_over1m_shp).

Tables

• Supplementary Data 1. Flood exposure in 2020 at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD1_Exposure_2020_Natl)
• Supplementary Data 2. Flood exposure in 2050 at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD2_Exposure_2050_Natl)
• Supplementary Data 3. Flood exposure in 2020 at the city scale (persons) (Tables/Supplementary_Data.xlsx; sheet: SD3_Exposure_2020_City)
• Supplementary Data 4. Flood exposure in 2050 at the city scale (persons) (Tables/Supplementary_Data.xlsx; sheet: SD4_Exposure_2050_City)
• Supplementary Data 5. Increases in flood exposure attributable to climate-driven floodplain change at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD5_Inc_Climate_Natl)
• Supplementary Data 6. Increases in flood exposure attributable to urban expansion at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD6_Inc_UrbanExp_Natl)
• Supplementary Data 7. Increases in flood exposure attributable to the compound effect of urban expansion and climate-driven floodplain change at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD7_Inc_Compound_Natl)
• Supplementary Data 8. Decreases in flood exposure attributable to climate-driven floodplain change at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD8_Dec_Climate_Natl)
• Supplementary Data 9. Decreases in flood exposure attributable to urban shrinkage at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD9_Dec_UrbanShrink_Natl)
• Supplementary Data 10. Decreases in flood exposure attributable to the compound effect of urban shrinkage and climate-driven floodplain change at global, continental, income-group, and national scales (persons) (Tables/Supplementary_Data.xlsx; sheet: SD10_Dec_Compound_Natl)
• Supplementary Data 11. City-scale increases in flood exposure attributable to climate-driven floodplain change (persons) (Tables/Supplementary_Data.xlsx; sheet: SD11_Inc_Climate_City)
• Supplementary Data 12. City-scale increases in flood exposure attributable to urban expansion (persons) (Tables/Supplementary_Data.xlsx; sheet: SD12_Inc_UrbanExp_City)
• Supplementary Data 13. City-scale increases in flood exposure attributable to the compound effect of urban expansion and climate-driven floodplain change (persons) (Tables/Supplementary_Data.xlsx; sheet: SD13_Inc_Compound_City)
• Supplementary Data 14. City-scale decreases in flood exposure attributable to climate-driven floodplain change (persons) (Tables/Supplementary_Data.xlsx; sheet: SD14_Dec_Climate_City)
• Supplementary Data 15. City-scale decreases in flood exposure attributable to urban shrinkage (persons) (Tables/Supplementary_Data.xlsx; sheet: SD15_Dec_UrbanShrink_City)
• Supplementary Data 16. City-scale decreases in flood exposure attributable to the compound effect of urban shrinkage and climate-driven floodplain change (persons) (Tables/Supplementary_Data.xlsx; sheet: SD16_Dec_Compound_City)
• Supplementary Data 17. Results of the uncertainty analysis (Tables/Supplementary_Data.xlsx; sheet: SD17_Uncertainty)
• Supplementary Data 18. City-scale urban resilience groups (Tables/Supplementary_Data.xlsx; sheet: SD18_Resilience_Groups)
• Supplementary Data 19. Multiple linear regression results (Tables/Supplementary_Data.xlsx; sheet: SD19_Regression)
• Supplementary Data 20. Accuracy assessment of the urban expansion simulation (Tables/Supplementary_Data.xlsx; sheet: SD20_UrbanExp_Accuracy)
• Supplementary Data 21. Merging process for adjacent cities and urban agglomerations (Tables/Supplementary_Data.xlsx; sheet: SD21_City_Merging)
