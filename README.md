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
-	Historic electricity demand data came from the National Grid ESO Data Portal at https://www.nationalgrideso.com/data-portal/historic-demand-data.
-	Weather data was sourced from the Met Office’s Midas-open dataset at https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1.
-	Bank holiday data came from a UK government website https://www.gov.uk/bank-holidays.



**Next steps:**

-Try fitting and evaluating a SARIMAX model on the natural log of live births per month data with seasonal factors included.

-Look at using pmdarima Auto ARIMA model to automate the calculations in creating an ARIMA model and see how the model compares with the model ARIMA(0,2,1) where I determined the p,d and q parameters. 

-Read up on CARIMA models as described in article 'Projecting age-specific fertility rates by using time-series methods' https://pubmed.ncbi.nlm.nih.gov/12316169/.

**Things I would do differently next time:** 
-	In retrospect I would have perhaps chosen completely different domain and dataset
-	Using data on births 

