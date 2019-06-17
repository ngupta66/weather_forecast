# Deep Neural Network for Weather Time Series Forecasting

Forecasting future values of a time series plays an important role in nearly all fields of science and engineering, such as economics, finance, business intelligence and industrial applications, also in real world applications such as speech recognition, real time sign language translation, finance markets, weather forecast etc. Deep Learning algorithms are known to perform best when there is a massive dataset available for learning. Not every time series problem has massive dataset available. In that case advanced ML algorithms are available for time series applications. Because of the nature of time series analysis problem where two values of the same feature in two different time steps are considered as different features, the data size available for processing becomes larger. It is hard to decide which algorithms will perform better for a medium size dataset. The recommendation made in this project can be useful for anyone looking for best ML/DL algorithms for medium size time series problem dataset.

### Data Set Used
I used Historical hourly Weather Data from Kaggle website. The dataset contains ~5 years of high temporal resolution (hourly measurements) data of various weather attributes, such as temperature, humidity, air pressure, etc. There is non-temporal data such as longitude and latitude of cities, which is also used in forecasting. Link to data set: https://www.kaggle.com/selfishgene/historical-hourly-weather-data

### Libraries Used
Different Python libraries are used for executing different Machine Learning and Deep Learning Models. LinearRegression and RandomForest from Sci-kit Learn, ARIMA model from Statsmodel, LSTM and MLP from Tensorflow Keras Functional APIs are used.

### Hardware Configuration
To execute the Deep learning Model, a distributed VM in Google Cloud with 8 core CPUs, 52 GB memory and 2 GPUs is used.

### Directory structure
Raw data from Kaggle website is cleaned and wrangled and stored is Data directory in several  formats used by different models. Here is the directory structure for the project:
- /data/raw - Raw data is stored in here.
- /data - Clean datasets are stored here  by weather_forecast_EDA.ipynb.
- /univar_models -  Notebooks for machine learning and deep learning univar_models
- /multivar_models  - Notebooks for machine learning and deep learning multivar_models.
- /results - Results of both univar_models and multi_var models are stored here.



