# Weather Forecasting App

A Python-based weather forecasting application that retrieves and displays weather information using the OpenWeatherMap API.

## Features

- Current weather data for any location
- 7-day weather forecast
- Supports multiple cities
- Displays temperature, humidity, wind speed, and more

## Prerequisites

- Python 3.x
- An API key from [OpenWeatherMap](https://openweathermap.org/api)



## Example

To get the current weather for London:

```python
from weather import get_current_weather

location = "London"
weather_data = get_current_weather(location)
print(weather_data)
