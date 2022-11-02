# Analyzing the Forecast Quality of Wind Energy in Germany from 2012 to 2020

 
## Background and Motivation 

In recent years, the share of wind energy in electricity generation in Germany has been increasing steadily.  Due to the legal regulations and targets of the German government, a further increase is to be expected.  

According to the German government's energy concept, 80% of total electricity consumption is to be covered by electricity generation from renewable energies (RE) by the end of 2050. To achieve this goal, electricity generation from intermittent RE such as wind energy is to be increased. 

In Germany, wind power is fed into the grid in the four control areas of the four transmission system operators (TSO).
In order to ensure security of supply, the four transmission system operators are required to keep electricity supply and demand in the grid in balance at all times. They must therefore know how much energy will be fed into the grid in which region in the coming hours and days. To ensure this, all planned and forecast consumption and generation must be reported in the form of schedules for the following day. In order for these schedules to be created, a forecast of the wind power feed-in is required. 

The short-term forecasts are based on one or more independent numerical. In this context, numerical weather forecasting is characterized by imprecise initial conditions, simplified topography, and a fuzzy description of physical and dynamic processes. Furthermore, the chaotic behavior of the atmosphere, especially strong abrupt changes in wind speed due to fog and snow situations are difficult to predict. Consequently, forecast errors are a real problem for TSOs with regard to grid security.

Derived from the above, it can be said that in the next few years, the focus should not only be on the addition of wind energy, but also on improving the forecasting accuracy of wind energy.

## Goals

Against this background, the aim of this project is to analyze the day-ahead forecast quality of wind energy feed-in in the control areas of the German TSOs and for the whole area of Germany for the years 2012 to 2020. Within the analysis, the seasonal fluctuations and also the forecast horizons are taken into account. This approach makes it possible to derive recommendations for action to ensure better forecast quality. 

## Structure

In the Notebook Data Cleaning the data on which the analysis is based is processed and then imported into a database.

The data set is then analyzed and visualized in [Tableau](https://public.tableau.com/app/profile/lily1503).

