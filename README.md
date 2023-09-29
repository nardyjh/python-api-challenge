# python-api-challenge

Module 6 - Challenge

# WeatherPy and VacationPy

WeatherPy and VacationPy are Python projects that help you explore and plan vacations based on weather conditions in cities around the world. WeatherPy retrieves current weather data for a list of randomly selected cities and analyzes the data to provide insights into temperature, humidity, cloudiness, and wind speed. VacationPy uses this weather data to identify ideal vacation spots with the desired weather conditions and nearby hotels.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [WeatherPy](#weatherpy)
  - [VacationPy](#vacationpy)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or later installed
- Dependencies installed (Pandas, Matplotlib, Requests, gmaps, hvPlot)
- API keys for OpenWeatherMap and Geoapify (sign up at [OpenWeatherMap](https://openweathermap.org/api) and [Geoapify](https://www.geoapify.com/))

### Installation

1. Clone the repository:

   git clone https://github.com/nardyjh/python-api-challenge.git

### Usage
### WeatherPy
WeatherPy retrieves current weather data for a list of randomly selected cities and generates visualizations to analyze weather patterns. To use WeatherPy:

Set up your OpenWeatherMap API key and create a file to store it, in this project this file is called api_keys.py.

### VacationPy
VacationPy uses weather data from WeatherPy to identify ideal vacation spots with the desired weather conditions and nearby hotels. To use VacationPy:

Set up your Geoapify API key and create a file to store it, in this project this file is called api_keys.py.

Ensure you have the output CSV file from WeatherPy containing weather data (output_data/cities.csv by default).

### Results
WeatherPy generates visualizations and analyses of weather data for cities around the world.

VacationPy provides a map with markers representing ideal vacation spots based on weather conditions. Hovering over a marker shows details about the city, hotel name, and more.

### Contributing
Contributions are welcome! 

### License
This project is licensed under the University of Toronto. 