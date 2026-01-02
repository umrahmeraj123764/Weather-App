A simple weather web application that shows current weather information for any city using HTML, CSS, JavaScript, and the OpenWeather API.
​

Overview
This project lets users enter a city name and fetch live weather data directly from the OpenWeather REST API.
​
It is designed as a beginner‑friendly project to practice making HTTP requests in JavaScript and updating the page dynamically with API responses.
​

Features
Search for a city and get real‑time weather details from OpenWeather.
​

Display temperature, weather description, humidity, and wind speed in a clean UI.
​

Basic error handling for invalid city names or failed API calls.
​

Tech Stack
Frontend: HTML for markup, CSS for layout and styling, vanilla JavaScript for logic.
​

Weather data: OpenWeather API for current weather information in JSON format.
​

Assets: Local icons/images to visually represent different weather conditions.
​

Getting Started
Clone the repository

bash
git clone https://github.com/umrahmeraj123764/Weather.git
cd Weather
This copies the project to your local environment.
​

Get an OpenWeather API key

Go to the OpenWeather website and create a free account.
​

Generate an API key from your account dashboard and copy it.
​

Configure the API key in the project

Open the main JavaScript file (for example script.js or app.js).
​

Replace the placeholder with your actual key:

js
const API_KEY = "YOUR_OPENWEATHER_API_KEY";
Save the file to apply the change.
​

Run the app

Open index.html directly in your browser, or

Start a local server (for example using VS Code Live Server) and navigate to the served URL.
​
Type a city name into the search box and view its current weather.


