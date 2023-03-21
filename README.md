# Hourly-Forecast-of-Bus-Demand
Time Series Forecasting of an Hourly Data

Executive Synopsis
--------------------
This analysis aims to forecast the hourly demand for buses in the municipalities of the Banana Republic. The central urban planning committee of Banana Republic provided a dataset containing two timestamped measurements per hour for the number of buses in use in each municipality. Ten municipalities (IDs ranging from 0 to 9) and two hourly measurements exist. The committee requested each municipality's hourly bus usage projections for the following week. The data have been modelled using a time series model and evaluated using the Mean Absolute Percent Error (MAPE).

According to the analysis, Prophet is an appropriate time series model for predicting bus demand. The initial solution yielded a MAPE of 24.944%, which was reduced to 24.238% using cross-validation with different parameters. The results indicate that the model can be used to predict hourly bus demand in the municipalities of the Banana Republic.

Data Analysis
--------------------
The committee-supplied dataset was analysed to identify any missing data or anomalies. It was determined that there were no missing data and that the data were complete, accurate, and ready for modelling.

To prepare the data for modelling, new features to view bus usage hourly, daily, and weekly were developed. The data was then separated into sets for training and testing. The training set included data from the first two weeks (beginning on 2017-07-22 and ending on 2017-08-04), while the testing set included data from the last two weeks (starting from 2017-08-05 to 2017-08-19).

Modeling and Outcomes
--------------------
Prophet was utilised to forecast the hourly bus demand over the next two weeks. The initial solution generated a MAPE of 24.944%. Then, Cross-validation was implemented with various parameters such as changepoint priority scale, seasonality priority scale, holidays priority scale, and seasonality mode to improve the model's accuracy. The optimal combination of parameters yielded an improved MAPE score of 24.238%.

The results indicate that the model can be used to predict hourly bus demand in the municipalities of the Banana Republic. Therefore, the central urban planning committee of Banana Republic can use the predicted hourly bus demand to plan and allocate resources efficiently.

Conclusion
--------------------
Using the Prophet model, the time series forecasting of hourly bus demand in the municipalities of the Banana Republic was completed successfully. The analysis determined that the model is accurate, and the results can be utilised for resource planning and allocation. Future work may include extending the scope of the research to incorporate multiple municipalities and investigating alternative time series models for comparison.
