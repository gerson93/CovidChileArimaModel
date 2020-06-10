# Forecasting Covid Cases in Chile with Arima Model

Here you have a simple Arima model for forecasting Covid cases for the next seven days in Chile. 

## Data Source

The data of COVID 19 in Chile, from 03-03-2020 to 25-04-2020 were collected from the official github of Ministerio de Ciencia de Chile (https://github.com/MinCiencia/Datos-COVID19/tree/master/output/producto5).


## Results

The fig 1 and fig 2 show the ACF and PACF plots of total cases used for estimating the best parameters (p, q, and d). The second differentiation was used.

![fig 1](https://github.com/gerson93/CovidChileArimaModel/blob/master/imagenes/Graf%202.png)
![fig 2](https://github.com/gerson93/CovidChileArimaModel/blob/master/imagenes/Graf%203.png)

The chosen parameters was p = 1, q = 1 and d = 2. With this values, the forecast for these next seven days is show in the fig 3
![fig 3](https://github.com/gerson93/CovidChileArimaModel/blob/master/imagenes/Graf%201.png)
