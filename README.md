🌤️ PyQt5 Weather App
A simple and elegant desktop weather application built with Python and PyQt5, using the OpenWeatherMap API. Enter a city name and get the current temperature, weather emoji, and description.

📸 Preview

🚀 Features
Enter city name and fetch real-time weather.

Displays temperature in Celsius.

Visual weather representation using emojis.

Handles API errors and connection issues gracefully.

Stylish, centered UI using PyQt5 layout and stylesheet.

🛠️ Requirements
Python 3.7+

PyQt5

requests

📦 Installation
bash
Copy
Edit
# Create and activate a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install PyQt5 requests
🔑 Get Your API Key
Go to OpenWeatherMap

Sign up and get your API key

Replace the API key in the code:

python
Copy
Edit
api_key = "YOUR_API_KEY_HERE"
🧪 How to Run
bash
Copy
Edit
python weather_app.py
💡 Example Usage
Run the app.

Enter a city name like London, Delhi, or Tokyo.

Click Get Weather.

View temperature, emoji, and weather description.

📂 File Structure
bash
Copy
Edit
weather_app.py       # Main application script
README.md            # Project documentation
🧯 Error Handling
Handles various network and API errors such as:

Invalid city names

Invalid API keys

Server timeouts

No internet connection

🎨 UI Design
Built with PyQt5 using QVBoxLayout and styled using Qt stylesheets:

Large fonts

Emoji support via Segoe UI Emoji

Center-aligned widgets
