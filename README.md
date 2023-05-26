Elias Hagos
05/25/2023
# python-api-challenge
# Weather Analysis

This project retrieves weather data from cities worldwide using the OpenWeatherMap API and analyzes the relationship between various weather variables and latitude.

## Introduction
The Weather Analysis project aims to showcase the relationship between weather variables (such as temperature, humidity, cloudiness, and wind speed) and latitude. The analysis involves retrieving weather data from over 500 cities worldwide using the OpenWeatherMap API and visualizing the data through scatter plots and linear regression.

## Requirements
To run the Weather Analysis project, you need the following requirements:
- Python 
- Jupyter Notebook
- citipy library
- OpenWeatherMap API key

## Installation
1. Clone the repository:

2. Install the required dependencies:


3. Obtain an API key from OpenWeatherMap by signing up at their website (https://openweathermap.org/) and creating an account.

4. Update the `config.py` file in the project directory with your API key:


## Usage
1. Open the Jupyter Notebook `WeatherPy.ipynb` in your Jupyter Notebook environment.

2. Run the notebook cells to execute the code step-by-step.

3. The notebook will generate scatter plots showcasing the relationships between latitude and various weather variables.

4. The notebook will also compute linear regression for each relationship and create additional scatter plots with regression lines.

## Results
The Weather Analysis project generates scatter plots and linear regression plots for the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

The scatter plots help visualize the distribution of weather variables across different latitudes, while the linear regression plots provide insights into the relationship between latitude and each weather variable.
# Vacation Planning with VacationPy

The VacationPy project helps you plan your future vacations by visualizing cities with ideal weather conditions on a map. It utilizes Jupyter notebooks, the GeoViews Python library, and the Geoapify API.

## Introduction
VacationPy allows you to explore cities worldwide and find destinations with your preferred weather conditions. It utilizes the weather data obtained in Part 1 of the project and combines it with the Geoapify API to find nearby hotels within a certain distance of each city.

## Requirements
To run the VacationPy project, you need the following requirements:
- Python 
- Jupyter Notebook
- geoViews library
- Geoapify API key

## Installation
1. Clone the repository:

2. Install the required dependencies:

3. Obtain an API key from Geoapify by signing up at their website (https://www.geoapify.com/) and creating an account.

4. Update the `config.py` file in the project directory with your API key:


## Usage
1. Open the Jupyter Notebook `VacationPy.ipynb` in your Jupyter Notebook environment.

2. Run the notebook cells to execute the code step-by-step.

3. The notebook will create a map that displays points for each city in the dataset, with the size of the points representing the humidity of each city.

4. The notebook will narrow down the dataset to find cities with your ideal weather conditions (e.g., temperature between 21 and 27 degrees, wind speed below 4.5 m/s, and zero cloudiness).

5. The notebook will utilize the Geoapify API to find hotels within 10,000 meters of each city's coordinates and create a new DataFrame (`hotel_df`) to store the city, country, coordinates, humidity, and hotel information.

6. The map will be updated to include hover messages with the hotel name and country for each city.

## Results
The VacationPy project provides a map visualization of cities with ideal weather conditions based on your preferences. The map showcases points representing cities, with the size of each point corresponding to the humidity of the respective city. Additionally, the map includes hover messages that display the hotel name and country for each city, allowing you to identify potential vacation destinations easily.
