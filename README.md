# SPY on Tomorrow
SPY on Tomorrow serves to aid both new and veteran investors in making financially sound decisions when investing in the stock market. The application provides the following market data:
* Historical closing price data (1 day prior).
* SPY (S&P 500 index ETF) predicted closing price trajectory for the next day.
###### (Add image here)

---
#
# Technical Requirements
###  Imported Libraries

 ![](Pictures/library_imports.png)

#

Generate ALPCACA API Keys 

![](Pictures/example_api_keys.png)


#

 The "warnings.filterwarnings" command removes or condenses warning errors to ease the reading experience of the programmer.

![](Pictures/warnings_filter.png)

(This code is optional)
#
### This application is compatible with the following platforms:
* MacOS
* Windows
* Linux 
#
#
---
# How the App Works
### Monte Carlo Simulator
This portion of the program similates 1000 possible outcomes based on the historical data (about 18 months of trading). Taking the average of that should give us the most likely outcome of the simulation.
We provide a low and high estimate based on the 25th percentile and 75th percentile as well. 



### Regression Prediction
Using multi-linear Regression, we can predict the outcome of the time-series data used. The independent variables were other world-wide region ETFs to predict the movement in the US by viewing the changes in the indices of other major, developed markets around the world. 
The accuracy score of the model is typically 95% or higher. 

![](Pictures/mc_graph.png)

#
#
---
#
#
# How to Use our App
Simply run the .exe or .py file. Once the application pop up, simply press the Predict button! 
#
#
---
#
#
# Meet the Creators of (App Name)
* Jarom Lemmon (Team Lead & Core Programmer)
* Jacquelin Chavez (GUI Lead Designer)
* Jonathan Frazure (Data Acquisition & Cleaning)
* Khareem Henderson (README Developer)

