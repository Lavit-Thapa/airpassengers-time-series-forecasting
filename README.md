# ✈️ AirPassengers Time Series Forecasting with ARIMA & SARIMAX 📈

Welcome to my hands-on exploration of **Time Series Forecasting** with the iconic AirPassengers dataset! 🚀 Today’s journey was all about decoding temporal patterns and building predictive models that see beyond the present.

## 🛠️ What I Did
- **Data Exploration & Visualization:** Plotted monthly passenger data from 1949-1960, highlighting clear trends and seasonality.
- **Stationarity Checks:** Conducted Augmented Dickey-Fuller tests confirming non-stationarity.
- **Transformations:** Applied differencing to stabilize the series.
- **ACF & PACF Analysis:** Analyzed autocorrelation structures to guide model selection.
- **Model Building:** Developed and compared:
  - **ARIMA(5,0,4)** - manually tuned based on initial diagnostics.
  - **Auto ARIMA** - automated parameter search for optimal ARIMA configuration.
  - **SARIMAX(3,0,2)** - final seasonal model suggested by Auto ARIMA.
- **Forecasting:** Generated and visualized forecasts using **SARIMAX(3,0,2)**, comparing predictions against actual passenger volumes.

## 🎯 Why This Matters
Time series forecasting unlocks insights hidden across time, whether anticipating passenger demand, inventory needs, or market movements. This hands-on session honed my ability to:
- **Diagnose stationarity**
- **Select optimal ARIMA/SARIMA models**
- **Visualize forecasts and assess model performance**

## 🌟 My Takeaways
Time series modeling is about more than algorithms, it’s about telling the story of data evolving through time. Each plot and parameter taught me how subtle changes impact predictions, making the process as enlightening as it is rewarding.
