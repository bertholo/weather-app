# WEATHER APP PROJECT

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Demo](#demo)
4. [steps](#steps)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Technologies Used](#technologies-used)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
This Weather App is a simple application that provides current weather information and forecasts for any city in the world that has a minimun population of 100.000 people. It fetches data from two APIs, a geo API and a weather API, then the data is displayed in a user-friendly interface.

## Features
- Current weather conditions (temperature, humidity, wind speed, feels like temperature and pressure)
- 7-day weather forecast
- Search functionality for cities worldwide
- Responsive design for mobile and desktop use

## Demo
[Link to live demo](https://bertholo.github.io/weather-app/)

![Weather App Screenshot]()

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
2. Install dependencies:
   ```bash
   npm install
3. Obtain an API key from openWeatherMap and GeoDB

### Usage
1. Create a .env file in the root directory and add your GeoBD and openWeatherMap API key:

   ```env
   REACT_APP_X_RapidAPI_Key=your_api_key_here
   REACT_APP_WEATHER_API_KEY=your_api_key_here
2. Start the application:

   ```bash
   npm start
3. View the app on your browser

### Configuration
* API Key: Make sure to replace your_api_key_here in the .env file with your actual API key.
* API Endpoint: By default, the app uses OpenWeatherMap API. You can change the API endpoint in the configuration file if necessary.

### Technologies Used
* React.js
* fetch (for API requests)
* CSS3 for styling

### Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
5. Open a pull request.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
