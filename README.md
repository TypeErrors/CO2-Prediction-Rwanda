# CO2-Emission-Prediction-Rwanda

# About

This data was obtained from Kaggle.com. 

The objective of this challenge is to create machine learning models that use open-source emissions data (from Sentinel-5P satellite observations) to predict carbon emissions.

Approximately 497 unique locations were selected from multiple areas in Rwanda, with a distribution around farm lands, cities and power plants. 

The data for this competition is split by time; the years 2019 - 2021 are included in the training data, 

and your task is to predict the CO2 emissions data for 2022 through November.

Seven main features were extracted weekly from Sentinel-5P from January 2019 to November 2022. Each feature (Sulphur Dioxide, 

Carbon Monoxide, etc) contain sub features such as column_number_density which is the vertical column density at ground level, 

calculated using the DOAS technique. You can read more about each feature in the below links, including how they are measured and variable definitions.

You are given the values of these features in the test set and your goal to predict CO2 emissions using time information as well as these features.

Sulphur Dioxide - COPERNICUS/S5P/NRTI/L3_SO2 Carbon Monoxide - COPERNICUS/S5P/NRTI/L3_CO Nitrogen Dioxide - COPERNICUS/S5P/NRTI/L3_NO2 Formaldehyde - 

COPERNICUS/S5P/NRTI/L3_HCHO UV Aerosol Index - COPERNICUS/S5P/NRTI/L3_AER_AI Ozone - COPERNICUS/S5P/NRTI/L3_O3 Cloud - COPERNICUS/S5P/OFFL/L3_CLOUD 

Important: Please only use the data provided for this challenge as part of your modeling effort. Do not use any external data, 

including any data from Sentinel-5P not provided on this page.
