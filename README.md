Geeting weather application 
 
#      PyQt5 Weather App 
 
A simple and elegant weather application built using **Python**, **PyQt5**, and the 
**OpenWeatherMap API**.   
It allows users to input a city name and receive real-time weather information including temperature, a 
descriptive emoji, and a short summary of the weather condition. 
 --- 
 
##          Preview 
 - Users enter a city name. - The app displays: 
  - 🌡 Temperature in Fahrenheit 
  - 🌤 Emoji based on weather condition 
  -      Description of the weather 
 --- 
 
##         Features 
 - Real-time weather fetching via [OpenWeatherMap](https://openweathermap.org/) - Clean, styled PyQt5 GUI - Error handling for network and API-related issues 
By Eng.Marwan Ahmed Ibrahim - Displays appropriate emoji for each weather condition 
 --- 
 
## 🛠 Requirements 
 - Python 3.x - `requests` library - `PyQt5` library 
 
### Install dependencies: 
 
```bash
pip install requests PyQt5 
```
  Setup 
1. Get your API key from OpenWeatherMap. 
2. Replace the placeholder API key in the code: 
api_key = "your_api_key_here" 
The current code includes a test key for demonstration. Replace it before production use. 
 
   Run the App 
python weather_app.py 
 
    Code Structure 
• WeatherApp class: The main GUI window and logic 
By Eng.Marwan Ahmed Ibrahim 
• get_weather(): Handles API call and error management 
• display_weather(): Updates the GUI with weather data 
• get_weather_emoji(): Maps weather condition codes to emojis 
 
  Error Handling 
Handles: 
• Invalid city names 
• API key errors 
• Network issues 
• Server timeouts 
• Specific HTTP error codes 
 
 
  Author 
Developed by [Marwan Ahmed Ibrahim] 
