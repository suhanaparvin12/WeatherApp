# Weather App

A simple web application to check the current weather of any city using the OpenWeatherMap API.

## Features

- Search for the weather by city name
- Display current temperature, humidity, and wind speed
- Display weather icons based on the current weather conditions
- Show error message for invalid city names


## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/suhanaparvin12/WeatherApp.git
    ```

2. Navigate to the project directory:
    ```bash
    cd weather-app
    ```

3. Open `index.html` in your browser.

## Configuration

To use the OpenWeatherMap API, you need to get your API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up). Replace the `apiKey` variable value in the `script` section of `index.html` with your API key:

```javascript
const apiKey = "YOUR_API_KEY";
