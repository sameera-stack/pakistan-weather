# Pakistan Weather Live

A single-page weather dashboard for 12 cities in Pakistan, built with plain HTML, CSS and JavaScript (no frameworks, no API key).

## Features

- Live current weather for 12 cities: temperature, feels-like, humidity, wind speed and elevation
- 7-day forecast with daily high/low temperature and rainfall
- Last 30 days of historical temperature for the selected city, with a line chart and summary statistics (average daily high, hottest day, coldest night, total rainfall)
- City comparison chart ranked by current temperature
- Celsius / Fahrenheit toggle
- Responsive layout with automatic dark mode

## Data source

Weather data comes from the free [Open-Meteo](https://open-meteo.com/) Forecast and Historical Weather APIs (CC BY 4.0). Historical data is usually about 5 days behind the current date.

## Run it

Open `index.html` in any browser with an internet connection. No installation needed.

To host it for free, push this folder to GitHub and enable GitHub Pages (Settings > Pages > Deploy from branch `main`).

## Tech

HTML, CSS, JavaScript (fetch API), SVG charts, Open-Meteo REST API.

## Author

Sameera Khalid
