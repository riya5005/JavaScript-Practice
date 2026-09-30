# Weather App 

This is a simple Weather App that I built using HTML, CSS and JavaScript. It uses the OpenWeather API to get the current weather details for a city entered by the user.

## Features

* Search weather by city name
* Shows current temperature
* Shows humidity
* Shows wind speed
* Changes the weather icon based on the weather condition
* Shows an error message if the city is not found
* Simple and responsive UI

## Tech Stack

* HTML
* CSS
* JavaScript
* OpenWeather API

## Project Structure

```text
Weather-App/
│
├── index.html
├── style.css
└── images/
    ├── search.png
    ├── cloud.png
    ├── clear.png
    ├── rain.png
    ├── drizzle.png
    ├── mist.png
    ├── humidity.png
    └── wind.png
```

## How It Works

The user enters a city name in the search box and clicks the search button.

JavaScript then sends a request to the OpenWeather API. The response contains the weather information for that city.

The app displays:

* City name
* Temperature in °C
* Humidity
* Wind speed
* Weather condition icon

For example, if I search for `Delhi`, the app fetches the current weather data for Delhi and updates the card with the results.

## API Used

I used the OpenWeather API for getting the weather data.

API URL:

```text
https://api.openweathermap.org/data/2.5/weather
```

The city name and API key are added to the request using JavaScript.

Example:

```text
https://api.openweathermap.org/data/2.5/weather?units=metric&q=Delhi&appid=YOUR_API_KEY
```

## Setting Up the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/weather-app.git
```

### 2. Open the project

Open the project folder in VS Code.

### 3. Add your API key

In `index.html`, add your OpenWeather API key:

```javascript
const apiKey = "YOUR_API_KEY";
```

### 4. Run the project

Open `index.html` in the browser.

You can also use the Live Server extension in VS Code.

## What I Learned

While making this project, I practiced:

* Working with APIs
* Using `fetch()`
* Using `async/await`
* Handling JSON data
* DOM manipulation
* Adding event listeners
* Updating HTML elements using JavaScript
* Handling invalid city names
* Changing images dynamically based on API data

## Future Improvements

Some things I would like to add later:

* 5-day weather forecast
* Current location weather
* Celsius/Fahrenheit option
* Search using the Enter key
* More weather details
* Better mobile responsiveness

## Author

**Riya**

B.Tech CSE - Data Science
