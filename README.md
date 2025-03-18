**Weather App**

**Description**
This is a simple Weather App built using HTML, CSS, and JavaScript. It fetches real-time weather data using the OpenWeatherMap API and displays the current weather conditions for any city entered by the user.

**Features**
Search for current weather by city name
Displays temperature, weather condition, humidity, and wind speed
User-friendly and responsive UI
Fetches live data from OpenWeatherMap API

**Technologies Used**

HTML
CSS
JavaScript
OpenWeatherMap API

**How to Use**

Clone this repository:
git clone <repository_url>
Open the index.html file in your browser.
Enter a city name in the search bar and click the search button.
The app will display the current weather details.

**API Setup**
Sign up at OpenWeatherMap to get your API key.
Replace YOUR_API_KEY in the JavaScript file with your actual API key:

**const apiKey = "YOUR_API_KEY";**

Go to this link use key from : https://home.openweathermap.org/api_keys

used this Built-in API request by city name - https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}

If you want you can also use city, state, country API

https://api.openweathermap.org/data/2.5/weather?q={city name},{state code},{country code}&appid={API key}

Edit above linke like this using key and add city name also add units= metric for: converts the temperature to Celsius instead of the default Kelvin in the OpenWeatherMap API response

Eg - https://api.openweathermap.org/data/2.5/weather?q=Fairborn&appid=b789d93e68fa1a6307e68a528945129e&units=metric

**Future Enhancements**
Add a 5-day weather forecast feature
Implement geolocation-based weather detection
Improve UI/UX with better animations and design

**Developed By**
Monali Khot

Feel free to contribute or suggest improvements!

