# 🌤️ PyQt5 Weather App

A simple and stylish desktop weather application built with **Python** and **PyQt5**, powered by the **OpenWeatherMap API**.

## 🚀 Features

- Real-time weather information by city name
- Displays:
  - Temperature in Celsius
  - Weather condition with emoji
  - Weather description (e.g., "clear sky", "light rain")
- Graceful error handling for invalid input or API issues
- Modern and clean user interface using Qt Stylesheets

## 🛠️ Requirements

- Python 3.7 or higher
- PyQt5
- requests

## 📦 Installation

```bash
pip install PyQt5 requests
```

## 🔑 API Key Setup

1. Sign up at [OpenWeatherMap](https://openweathermap.org/api) to get a free API key.
2. In the code, replace this line with your actual API key:

```python
api_key = "YOUR_API_KEY_HERE"
```

## 🧪 How to Run

```bash
python weather_app.py
```

## 💡 How It Works

- Enter a city name in the input box.
- Click the **"Get Weather"** button.
- The app fetches weather data using the OpenWeatherMap API and displays:
  - Temperature
  - A relevant emoji
  - A short description of the current weather

## 📂 File Structure

```
weather_app.py       # Main application file
README.md            # Project documentation
```


