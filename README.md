# Weather Forecast Application

![Weather App Screenshot](https://via.placeholder.com/800x600?text=Weather+Forecast+App)

A comprehensive weather forecast application that provides current weather conditions, hourly and 5-day forecasts, and specialized data for agriculture, climate, air quality, and flood risk.

## Features

- **Current Weather**: Real-time temperature, humidity, wind speed, pressure, visibility, and UV index
- **Forecasts**: 
  - Hourly weather predictions
  - 5-day weather forecast
- **Interactive Map**: Visual weather map showing current conditions
- **Specialized Data**:
  - Agriculture information and farming recommendations
  - Climate change data and trends
  - Air quality index and pollutant levels
  - Flood risk assessment
- **Responsive Design**: Works on all device sizes
- **Dynamic Background**: Changes based on current weather conditions
- **Unit Conversion**: Switch between Celsius and Fahrenheit

## Technologies Used

- HTML5
- CSS3 (with CSS variables for theming)
- JavaScript (ES6)
- [OpenWeatherMap API](https://openweathermap.org/)
- [Font Awesome](https://fontawesome.com/) for icons
- Various weather APIs for specialized data

## Installation

No installation required! Simply open the `index.html` file in any modern web browser.

## Usage

1. Enter a city name in the search box or click "My Location" to get weather for your current location
2. View current weather conditions and forecasts
3. Explore specialized data tabs:
   - Agriculture: Farming conditions and recommendations
   - Climate: Climate change trends and data
   - Air Quality: Pollution levels and health recommendations
   - Flood Risk: Flood probability and preparedness tips

## API Configuration

To use this application, you'll need to obtain API keys for:

1. OpenWeatherMap (required for basic weather data)
2. Climate API (optional for climate data)
3. Agriculture API (optional for farming data)
4. Flood API (optional for flood risk data)

Replace the placeholder API keys in the JavaScript section with your actual keys.

```javascript
// API Configuration
const API_KEY = 'YOUR_OPENWEATHERMAP_API_KEY';
const CLIMATE_API_KEY = 'YOUR_CLIMATE_API_KEY';
const AGRICULTURE_API_KEY = 'YOUR_AGRICULTURE_API_KEY';
const FLOOD_API_KEY = 'YOUR_FLOOD_API_KEY';
