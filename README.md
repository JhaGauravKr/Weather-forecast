# Weather Forecast Application  

## Description  
The Weather Forecast Application is a web-based project that allows users to view live weather updates for any city. By entering the name of a city, users can access:  
- **Current temperature**  
- **Humidity**  
- **Wind speed**  
- **Five-day weather forecast**  

This application is built using **HTML**, **CSS**, **JavaScript**, and the **OpenWeatherMap API** for fetching real-time weather data.  

## Features  
- **Live Weather Data:** Displays real-time weather conditions for any city.  
- **5-Day Forecast:** Provides weather predictions for the next five days.  
- **User-Friendly Interface:** Simple and intuitive design for seamless navigation.  

## Technologies Used  
- **HTML:** Structure and layout of the application.  
- **CSS:** Styling and responsive design.  
- **JavaScript:** Fetching and processing data from the API, and rendering it dynamically.  
- **API:** [OpenWeatherMap API](https://openweathermap.org/) for retrieving weather data.  

## Usage  
1. On the home page, enter the name of the city you wish to check the weather for.  
2. Press the "Search" button.  
3. View the live weather updates and 5-day forecast for the city.  

## API Configuration  
To run the project with live data:  
1. Get your free API key from [OpenWeatherMap](https://openweathermap.org/api).  
2. Replace `YOUR_API_KEY` in the JavaScript file with your API key:  
   ```javascript  
   const apiKey = 'YOUR_API_KEY';  
