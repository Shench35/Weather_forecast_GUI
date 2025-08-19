🌦️ Weather App (CustomTkinter + OpenWeatherMap API)

This is a simple desktop weather application built with Python using the CustomTkinter
 library for a modern UI and the OpenWeatherMap API for real-time weather data.

✨ Features

Search weather by city name

Handles offline mode (displays "No internet connection")

Detects invalid city names (displays "City not found")

Shows:

Current temperature in °C

Current weather condition (e.g., clear sky, rain, cloudy)

Clean and modern dark-themed interface

🛠️ Technologies Used

Python

CustomTkinter (UI framework)

Requests (HTTP requests to OpenWeatherMap API)

OpenWeatherMap API (real-time weather data)

🚀 How It Works

Enter a city name in the input box.

The app retrieves the latitude and longitude of the city via OpenWeatherMap’s Geocoding API.

It then fetches the current weather data using the coordinates.

The result is displayed in a simple and user-friendly interface.

📸 Screenshot (optional)

(You can add a screenshot of your app here if you like)

🔧 Setup

Clone this repository

Install dependencies:

pip install customtkinter requests


Get your free API key from OpenWeatherMap
.

Run the app:

python weather_app.py
