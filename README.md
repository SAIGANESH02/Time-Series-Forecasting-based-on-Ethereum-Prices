## Project Overview

The Ether cryptocurrency, which is based on the Ethereum project's blockchain for smart contracts, has long been the second most valuable cryptocurrency beside Bitcoin. In terms of time series analysis, despite its importance and the novel aspects of the entire Ethereum ledger ecosystem, Ether has received significantly less attention than Bitcoin. A machine learning-based time series analysis was used to anticipate the market price and stability of Ethereum in the Crypto-market. Time-series analysis can forecast future price fluctuations in Ethereum. For time series analysis, we employed LSTM, moving averages, ARIMA, and FBProphet as machine learning approaches.

## Methods Used

### Moving Average

A moving average is a technique to get an overall idea of the trends in a data set; it is an average of any subset of numbers. This simple moving average model gives the next observation is the mean of all past observations creating a constantly updated average price.

### ARIMA

- Auto Regressive Integrated Moving Average (ARIMA) models explains a given time series based on its own past values, that is, its own lags (p) and the lagged forecast errors (q), so that equation can be used to forecast future values. The 'd' parameter represents the number of times that the data have to be differenced to produce a stationary signal that has a constant mean over time. This captures the integrated nature of ARIMA.

- Auto ARIMA automatically generates the optimal combination of (p,q,d) which would be suitable for the data set to provide better forecasting.

### Prophet
![Prophet](https://user-images.githubusercontent.com/53213766/174355008-8a0d295e-f3a3-4d8d-811c-74544f12f6c7.png)

FB-Prophet is an auto machine learning software that uses seasonality to predict data on a daily, weekly, monthly, and yearly basis. Seasonality is something that data observers notice recurring after a certain period of time; the best example of seasonality is the shift in ice-cream sales between winter and summer. This is critical for the greatest possible data fit. FbProphet can be used to fit and predict data based on any seasonality, and then to obtain components for such predictions, which can be changed in the trend of data based on weekly, monthly, and daily

### Long-Short-Term Memory (LSTM)

An LSTM is a Recurrent Neural Network that is able to store past information that is important, and forget the information that is not. It uses the short-term memory processes to create longer memory and introduces the concept of gates for controlling the flow of information in the network by having input, output and forget gates.

![LSTM](https://user-images.githubusercontent.com/53213766/174353414-de0db9fa-ed58-4ac0-bd58-aa09ccae606f.png)

## Results

Fig 1: - Visualising Ethereum stock data from January 2018-2020.
![image](https://user-images.githubusercontent.com/53213766/174353939-7f0e3326-55b8-454a-8836-2a33db6055ae.png)

Fig 2: - Forecasted values using Moving Averages model
![image](https://user-images.githubusercontent.com/53213766/174353960-422875f4-7899-493e-81f8-948ca98014f7.png)

Fig 3: - RMSE value for the Forecasted values.
![image](https://user-images.githubusercontent.com/53213766/174353981-2dc86d73-68fb-406f-b628-d04b1fab3c82.png)

Fig 4: - Time series plot of Closing prices.
![image](https://user-images.githubusercontent.com/53213766/174354021-e4f61785-44bc-43f8-b873-32d4785000c8.png)

Fig 5: - Log plot of the closing prices
![image](https://user-images.githubusercontent.com/53213766/174354078-3e211a23-a364-4434-a5e0-3b2939bafe68.png)

Fig 6: - Results from prophet model.
![image](https://user-images.githubusercontent.com/53213766/174354101-f9ec0c51-aa4b-4804-8f84-1e6f51ecfe46.png)

![image](https://user-images.githubusercontent.com/53213766/174354170-02be177b-73a7-4dd4-8490-461cf4de318f.png)

Fig 7: - Tabular representation of results from prophet model
![image](https://user-images.githubusercontent.com/53213766/174354201-ea3426d7-1359-4fe1-898e-a4c7ec304581.png)

Fig 8: - Residual Plot for ARIMA model
![image](https://user-images.githubusercontent.com/53213766/174354221-9c8b0447-36c6-4fcd-b83b-bda597af0aa4.png)

Fig 9: - Arima model representation
![image](https://user-images.githubusercontent.com/53213766/174354252-6ed7fd62-2cda-4637-bb80-9885db65cdb3.png)

Fig 10: - RMSE value for ARIMA model forecast
![image](https://user-images.githubusercontent.com/53213766/174354266-71c45bb8-ea46-4e94-a126-aa8c3182df0f.png)

Fig 11: - LSTM model representation.
![image](https://user-images.githubusercontent.com/53213766/174354274-3058be26-cf06-4257-9e86-3dbb7bb3ac3d.png)

Fig 12: - RMSE value for LSTM model forecast
![image](https://user-images.githubusercontent.com/53213766/174354285-40caf08c-e551-4c9f-9ddd-6cc1866cb5ad.png)

Fig 13: - Tabular representation of the RMSE values.
![image](https://user-images.githubusercontent.com/53213766/174354386-30e6b896-223a-4df0-a0a1-549df4633287.png)

Thank You :)
### Sai Ganesh N

