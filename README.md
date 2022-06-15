# Project_07_ForecastElectricityDemand
### <b>ABOUT</b>
This project aims to help Enercoop forecast demand for electricity. Enercoop is a cooperative society that has developed thanks to France's electricity market liberalization. It specializes in renewable energies.

However, most of these renewable energies are intermittent, so it is challenging to predict electricity production capacities. In addition, users' demand for electricity varies over time and depends on parameters such as the weather (temperature, brightness, etc.). The whole challenge is to match supply and demand!

### <b>CONDITIONS</b>
This project requires mastering data manipulation in Python or R, linear regression type modeling, and different time series modeling (AR, MA, ARMA, ARIMA, SARIMA, Holt-Winters, etc.)

### <b>SKILLS ASSESSED</b>
- Master the notions of components and decomposition models
- Master smoothing methods and the Holt-Winters method
- Master the SARIMA method
- Graph a time series

### <b>DATA</b>
The monthly data on total electricity consumption in energy can be downloaded through this [link](https://www.rte-france.com/eco2mix/telecharger-les-indicateurs).

The weather data can be downloaded [here](https://cegibat.grdf.fr/simulateur/calcul-dju) to rectify the temperature effect data.

# <b>MISSIONS</b>
This project solely focuses on predicting electricity demand.

### Mission n°1
The monthly consumption data for the temperature effect (due to electric heating) is corrected using linear regression.

### Mission n°2
Carried out a seasonal adjustment of the consumption (obtained after correction) thanks to the moving averages.

### Mission n°3
Forecasted 1 year of electricity consumption (corrected for the temperature effect) using the Holt-Winters method (exponential smoothing) and then the SARIMA method on the time series.

### Mission n°4
For each processing carried out (correction of the temperature effect, seasonal adjustment, etc.), we will graph 2 superimposed time series (before and after processing).
