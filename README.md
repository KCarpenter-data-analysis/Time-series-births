# Time-series-births

**PROJECT OVERVIEW**

**Aims:**

The project analyses aspects of data on live births and fertility rates over time. Using data from the ONS on the number of live births per month and the general fertility rate (number of live births per 1,000 women aged 15-44) in England and Wales (1938-2022) to create time series. It then go on decompose the time series before fitting various models to the time series to see how well they are at forecasting. I then consider how big an impact the legalisation of abortion had on declining general fertility rates.

**Objectives:** 
-	Use real-life data to generate time series using Python.
-	 Decompose time series and then determine the best-fitting model for forecasting future values of the time series.  

**Programs Used:**

Python within a Jupyter Notebook. 

**Data Sources:**
The data came from the ONS. It is available at https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/livebirths/bulletins/birthsummarytablesenglandandwales/2022refreshedpopulations. 


**Next steps:**

-Try fitting and evaluating a SARIMAX model on the natural log of live births per month data with seasonal factors included.

-Look at using pmdarima Auto ARIMA model to automate the calculations in creating an ARIMA model and see how the model compares with the model ARIMA(0,2,1) where I determined the p,d and q parameters. 

-Read up on CARIMA models as described in article 'Projecting age-specific fertility rates by using time-series methods' https://pubmed.ncbi.nlm.nih.gov/12316169/.

**Things I would do differently next time:** 
-	In retrospect I would have perhaps chosen completely different domain and dataset to 
-	Using data on births 

**REFERENCES**
Data source: Office for National Statistics (ONS), released 23 February 2024, ONS website, statistical bulletin, Births in England and Wales: 2022 (refreshed populations)
