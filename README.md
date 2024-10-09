# weather-forecast
weather forecasting for energy generation company and anomaly detection in time series data


to load model and predict with model
# load
import pickle
with open('wind_forecast_model.pkl', 'rb') as f:
    model = pickle.load(f)

# prediction might give an error cuz the input features need to be operated upon
model.predict(X[0:1])