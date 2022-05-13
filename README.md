# Wildfire-Data-Analysis

**Description:**
Implement a fire data analysis based on different datasets. The location should be of YOUR CHOICE, feel
free to investigate an area that is familiar to you or that you are interested in. The area of interest should contain a
min. of 10x10km and not be larger than approx. 500 x 500km, the max timespan should not be larger than the last
10 years.

**Input data:**
(you may need to register at the climate data store first.)
  - Burned Area: MODIS burned area (grid OR pixel) [https://cds.climate.copernicus.eu/cdsapp#!/dataset/satellite-fire-burned-area?tab=overview]
**(Optional) additional Input data:**
  - Vegetation / land cover classes: ESA cci landcover (Attention: Very large files since download will default
to global coverage. Option: Import as “static” feature containing only 1 year). [https://cds.climate.copernicus.eu/cdsapp#!/dataset/satellite-land-cover?tab=overview]
  - meteorological data, 2 options, depending on your timeframe:
      - ERA5 hourly [https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-land?tab=form]
      - ERA5 monthly [https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels-monthly-means?tab=overview]

**Suggested Workflow:**
- Create a Github account and a repository to keep track of your source code or use your existing account
- decide on an area of interest, check if this area has wildfire occurrences before, e.g. with NASA FIRMS
- familiarize yourself briefly with the content, spatial and temporal resolution of the available datasets
- form 2 hypotheses you would like to test based on the data.
- select variables for your area of interest based on your hypothesis
- download selected data, overcome potential challenges with the data download
- test your hypothesis using data visualization and data analytics.
 
**Required Output:**
- Jupyter notebook on your github account that includes the hypothesis & data analysis
**(optional) output:**
- data download scripts
- data processing can either be done in an additional notebook or python script, depending on your personal
preference

**Additional information:**
- To explore netcdf data you can use the Panoply NetCDF viewer: https://www.giss.nasa.gov/tools/panoply/
