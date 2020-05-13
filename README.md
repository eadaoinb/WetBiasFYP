# WetBiasFYP
FYP for Assessment of Wet Bias in Weather Forecast Providers UCD

The predicted precipitation amounts are all in folder Data for every provider and location.

Running code requires Jupyter Notebooks.

In Final Notebooks you will find the code used for the report. 

The code should be run as follow:
1. PullingObservedXML.ipynb - gets observed amounts for Met Eireann
2. ObservedAmountsJSON.ipynb -  gets observed amounts for DarkSky
3. GettingForcastValuesJSON.ipynb -  gets forecasted amounts from file Data for DarkSky  and exports to csv file forecastNew.
4. GettingForcastValuesXML.ipynb - gets forecasted amounts from file Data for XML  and exports to csv file forecastXMLNew.
5. GettingForcastValuesYR.ipynb- gets forecasted amounts from file Data for YR and exports to csv file forecastYR.
6. ForecastvObservedYR.ipynb - compares observed vs predicted amounts for YR - gets obsevred by averaging the observed met and darksky values.
7. ForecastvObservedXML.ipynb -  compares observed vs predicted amounts for Met Eireann.
8. ForecastvObservedJSON.ipynb -  compares observed vs predicted amounts for DarkSky.

These notebooks return the CSV files in the Notebooks and Final CSV files folder.




