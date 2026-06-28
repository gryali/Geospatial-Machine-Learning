# Spatial-Aware Machine Learning
Herein, a spatially-aware machine learning optimization framework is presented which implements LightGBM in a streamlined Bayesian optimization workflow that incorporates Local Outlier Factor thresholding and Eigenvector Spatial Filtering with 5-fold Spatial Block Cross-validation to model four distinct GEDI-derived forest structure characteristics using multi-source earth observation (EO) data accross a tropical lancape in Papua New Guinea (PNG). The multi-source EO data is an integration of Sentinewl-1 SAR, Sentinel-2 optical imagery, and AlphaEarth Satellite Embeddings, and climatic (TerraClimate: precipitation and temperature) and Topographic (Copernicus FABDEM: DEM, slope, and aspect) datasets. 

For demonstration purposes, only canopy height (RHm) and canopy cover (TCC) modelling are provided here from which spatial predictions are derived. Ultimately, a comprehensive forest structure index (FSI) is synthesized from the GEDI multi-metric performance-weighted summation of these forest structure spatial predictions. The FSI acts as an operation landscape metric representing multi-dimentional forest structure variability to support forest and aboveground biomass monitoring and dynamics. FSI with inidividual canopy height and cover metrics spatially portrayed and compared with the PNG National Forest Inventory (NFI) data via a stratified validation approach, provides the first GEDI-derived spatially-explicit forest structure wall-to-wall mapping effort specific to PNG.

# Paper Highlights
- Introduction of a mean GEDI canopy height metric (RHm)
- Development of spatially-aware LightGBM optimization framework
  - Streamlined Bayesian Optimizer
  - Local Outlier Factor thresholding
  - Eigenvector Spatial Filtering
  - 5-fold Spatial Block Cross-validation
- Creation of  a comprehensive forest structure index (FSI) from GEDI multi-metric model predictions
- First spatially-explicit GEDI-derived forest structure wall-to-wall mapping effort specific to PNG

<img width="2752" height="1504" alt="SA-LGBM_Infograph#_" src="https://github.com/user-attachments/assets/3a87a259-85e1-4e5e-a482-2e7610d2a0d6" />
