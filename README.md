# Weather-App

This repository contains a weather application built with Node.js and Express, which fetches weather data based on the user’s location.

[![Github repo size](https://img.shields.io/github/languages/code-size/adarshjoshy/node3-weather-website)](https://github.com/adarshjoshy/node3-weather-website)
[![GitHub top language](https://img.shields.io/github/languages/top/adarshjoshy/node3-weather-website?color=green)](https://github.com/adarshjoshy/node3-weather-website)
[![GitHub](https://img.shields.io/github/license/adarshjoshy/node3-weather-website)](https://github.com/adarshjoshy/node3-weather-website)

### Features
<ul>
  <li>Fetches current weather data based on an address provided by the user.</li>
  <li>Uses <i>Mapbox API</i> for geocoding and <i>WeatherStack API</i> for weather data.</li>
  <li>Handles errors gracefully, such as missing address or failed weather retrieval.</li>
  <li>Dynamic pages rendered using <i>Handlebars (HBS)</i>.</li>
  <li>Responsive and interactive front-end.</li>
</ul>

### Instructions
The app uses `Node.js` with `Express.js` to serve the application and fetch weather data. To run the application locally:
1. Clone this repository.
2. Run `npm install` to install the required dependencies.
3. Start the server by running `node app.js`.

### Programs/Features
<ol>
  <li>Fetch weather details for a given location (latitude and longitude).</li>
  <li>Handle missing or incorrect location inputs gracefully.</li>
  <li>Render dynamic web pages such as home, about, and help pages using Handlebars.</li>
  <li>Display a 404 page for invalid URLs or pages.</li>
</ol>

### APIs Used
- <b>WeatherStack API</b> - Provides current weather details (temperature, humidity, etc.) for any given location.
- <b>Mapbox API</b> - Used to convert addresses to latitude and longitude.
