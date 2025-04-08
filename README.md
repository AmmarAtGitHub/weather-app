# weather-app

## Project Description
This is a simple weather application that uses the OpenWeatherMap API. Users can enter a city name to get current weather information including temperature, description, and additional details. The application is built using vanilla JavaScript, HTML, and CSS, ensuring a lightweight and efficient user experience.

## Features
- Real-time weather data
- Temperature in Celsius
- Weather description with icon
- Details like "feels like" temperature, humidity, and wind speed

## Setup Instructions

1. **Clone the Repository**
```
git clone https://github.com/AmmarAtGitHub/weather-app.git
cd weather-app
```

2. **Get an OpenWeatherMap API Key**
   * Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/)
   * Go to "My API Keys" in your account dashboard
   * Copy your API key

3. **Add Your API Key to the Project**
   * Open the JavaScript file
   * Replace `YOUR_API_KEY` with your actual API key
   * For example: `const apikey = "abc123def456ghi789";`

4. **Open the Application**
   * Open the HTML file in your browser to use the app

## Important Security Notes
  * Never commit your API key to GitHub
  * Use environment variables instead
  * Add any files with your API key to `.gitignore`

## How It Works
The app uses JavaScript to:
1. Get the city name from the input field
2. Send a request to the OpenWeatherMap API
3. Process the response data
4. Update the webpage with weather information
