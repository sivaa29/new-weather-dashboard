Weather Dashboard
Introduction
In this task, I built a Weather Dashboard frontend application using React that interacts with the OpenWeatherMap API to provide weather data. The application allows users to search for a city and view the current weather as well as the 5-day forecast. The goal is to demonstrate skills in building a user-friendly interface, fetching data from external APIs, and handling API responses effectively.

Features
Search Functionality: Users can input the name of any city, and the application will fetch the current weather and a 5-day forecast.
Weather Dashboard: Displays current weather conditions, including:
City Name
Temperature
Weather Description (e.g., Clear, Cloudy, Rainy)
Wind Speed
Humidity
Weather icon for visual representation
5-Day Forecast: Provides the daily weather forecast, including temperature and weather description for the next 5 days.
Error Handling: The application shows appropriate error messages if:
The city is not found.
There is an issue with the API request or network connection.
Responsive Design: The UI is responsive and provides an optimized experience for both desktop and mobile devices.
API to Use
OpenWeatherMap API: The weather data is fetched from the OpenWeatherMap API.
API URL: https://openweathermap.org/api
You can sign up on the OpenWeatherMap website and get a free API key to access weather data.
Technical Requirements
Frontend (React)
Search Functionality:

A search bar is provided where users can input a city name.
On submitting the search, the application fetches the current weather and a 5-day forecast for the searched city from the OpenWeatherMap API.
While the data is being fetched, a loading feedback is displayed to the user.
Weather Dashboard:

Displays the current weather for the searched city, including:
City Name
Temperature
Weather Description (e.g., Clear, Cloudy, Rainy)
Wind Speed
Humidity
Weather Icon representing the weather conditions.
Shows the 5-day forecast with temperature and weather description for each day.
Error Handling:

Displays appropriate error messages if:
The city is not found (e.g., invalid city name).
There are issues with fetching data from the API (e.g., API request failure or invalid API key).
Handles network errors gracefully, with clear messages guiding users to check their internet connection.
Styling:

The app is styled using Bootstrap for quick and responsive UI design.
The layout adapts to both desktop and mobile screens, ensuring a user-friendly experience across different devices.
User Feedback:

The user interface provides feedback for successful data retrieval and errors.
Error messages are displayed prominently, while loading feedback is shown during data fetch.
The weather data is displayed clearly, ensuring it’s easy for users to understand the weather conditions.
Getting Started
Prerequisites
To run the app locally, you need to have Node.js and npm installed on your machine.

Install Node.js and npm:

Download and install Node.js from https://nodejs.org.
This will also install npm (Node Package Manager) to manage project dependencies.

Install Dependencies: Navigate to the project directory and run the following command to install the necessary dependencies:

cd weather-dashboard
npm install

Running the App
Once all dependencies are installed, you can run the application locally using the following command:

npm start

This will start the development server and open the app in your default web browser at http://localhost:3000.
