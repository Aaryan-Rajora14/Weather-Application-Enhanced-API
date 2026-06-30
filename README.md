# Weather Pro

A simple and modern weather application built with Flask, HTML, CSS, and JavaScript. It allows users to search for any city or use their current location to view the current weather, hourly conditions, and a 3-day forecast.

## Features

- Search weather by city name or location
- Use current device location for local weather
- Display current temperature, humidity, wind speed, pressure, and UV index
- Show hourly weather for the current day
- Show a 3-day forecast
- Toggle between Celsius and Fahrenheit
- Toggle between dark and light themes

## Tech Stack

- Python
- Flask
- JavaScript
- Tailwind CSS
- wttr.in weather API

## Project Structure

- `app.py` - Main Flask backend and API route
- `templates/index.html` - Main UI layout
- `static/js/app.js` - Frontend weather logic and rendering
- `static/css/styles.css` - Additional styling

## Installation

1. Make sure Python is installed on your system.
2. Install the required packages:

```bash
pip install flask requests
```

## Running the App

1. Start the Flask server:

```bash
python app.py
```

2. Open your browser and visit:

```text
http://127.0.0.1:5000
```

## API

The app fetches weather data from the wttr.in API using the following endpoint:

```text
/api/weather?location=CityName
```

Example:

```text
/api/weather?location=London
```

## Notes

- The app depends on internet access to fetch weather data.
- Weather data is provided by wttr.in and may vary slightly depending on the service.

## License

This project is open for learning and personal use.
