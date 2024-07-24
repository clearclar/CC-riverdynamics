# CC-riverdynamics
Tracking river dynamics using dense time series in Google Earth Engine.
Find the GEE code here https://code.earthengine.google.com/17427b9be2db4ab5f06b6b2c8eee3e35 and in the GEE_code file.

Taking advantage of the long time series of the Landsat data archive and its high spatial resolution, this study aimed to create flood maps of maximum water extent and water cover duration for every hydrological year in the Naryn river watershed (Kyrgyzstan). The spectral indices Modified Normalized Difference Water Index (MNDWI), Automated Water Extraction Index for shadow (AWEIsh) and non-shadowy areas (AWEInsh) were applied for the detection of annual flooding dynamics. In-situ discharge data was furthermore used to validate the remote sensing results. 
Due to the long temporal coverage, the resulting data would enable a detailed analysis of flood events over several decades. The processing was completed in the Google Earth Engine (GEE) for the entire Naryn watershed from April to October using Landsat data from 1988 to 2023. Delineating water bodies and tracking changes in flood extent and duration can contribute to water management, disaster control and climate analysis.

Information on the indices can be found in

Laonamsai, J.; Julphunthong, P.; Saprathet, T.; Kimmany, B.; Ganchanasuragit, T.; Chomcheawchan, P.; Tomun, N. Utilizing NDWI, MNDWI, SAVI, WRI, and AWEI for Estimating Erosion and Deposition in Ping River in Thailand. Hydrology 2023, 10, 70, doi:10.3390/hydrology10030070.

and

Feyisa, G.L.; Meilby, H.; Fensholt, R.; Proud, S.R. Automated Water Extraction Index: A New Technique for Surface Water Mapping Using Landsat Imagery. Remote Sensing of Environment 2014, 140, 23–35, doi:10.1016/j.rse.2013.08.029.

Maps of AWEI no-shadow for selected areas within the catchment over four different years.
<p align="center">
  <img src="awei_nsh_ext.png" width="350">
  <img src="awei_nsh_dur.png" width="350">
</p>

