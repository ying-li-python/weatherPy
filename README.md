# weatherPy
<img src="https://images.unsplash.com/photo-1465429103920-30e481ab35b4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"> 

Spring is here! It's the first day of April so we would like to gather weather data to observe metrics such as temperature, humidity, cloudiness, and wind speed for cities chosen at random based on their unique coordinates (latitude/longitude) on Earth. 

## Resources 
- [OpenWeatherMap API](https://openweathermap.org/api) 

## Getting Started 
- Install the [CitiPy](https://github.com/wingchen/citipy) module to gather names of ~500 cities 
- Get unique API key from [OpenWeatherMap](https://openweathermap.org/api) to access weather information 
- In this folder, the api key has been hidden. Before running the script in Jupyter Notebook, you need to create a new file called config.py and create a string called api_key that contains your API key.

## Methods 
In the Jupyter Notebook file, citipy was used to gather names of cities at random. Weather data for these cities were retrieved through OpenWeatherMap and stored using Pandas. Matplotlib figures were generated to analyze data trends. 

## Results and Analysis
- Please see Jupyter Notebook file for reference. 

#### Latitude vs. Max Temp 

<img src="https://raw.githubusercontent.com/ying-li-python/weatherPy/master/Images/lat_vs_temp.png">

Weather is generally warmer in the southern hemispehere, and +/- 20 degrees from the equator. Interestingly, the weather in the northern hemisphere is significantly lower than the southern hemisphere during this time of year.

#### Latitude vs. Humidity

<img src="https://raw.githubusercontent.com/ying-li-python/weatherPy/master/Images/lat_vs_humidity.png"> 

There is no strong relationship between latitude and humidity. It is interesting to observe that humidity ranges from 20-100% in both the northern and southern hemispheres at this time.

#### Latitude vs. Cloudiness

<img src="https://raw.githubusercontent.com/ying-li-python/weatherPy/master/Images/lat_vs_cloudiness.png"> 

There is no strong relationship between latitude and cloudiness. However, there is a strong band of cities that resides at 0 and 90% cloudiness.


#### Latitude vs. Wind Speed 

<img src="https://raw.githubusercontent.com/ying-li-python/weatherPy/master/Images/lat_vs_windspeed.png"> 

There is no strong relationship between latitude and wind speed. It is interesting to note that a good number of cities in both northern and southern hemispheres have low wind speeds, between 0-15 mph.


## Author
Ying Li

