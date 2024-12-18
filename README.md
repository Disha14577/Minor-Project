# Weather-app
A simple weather app built with **HTML**, **CSS**, and **JavaScript** that provides real-time weather information for any city around the world. The app fetches weather data from the **OpenWeatherMap API** and displays the current temperature, humidity, wind speed, and weather conditions.
## Table of contents

- [About](#About)
- [Project Plan](#ProjectPlan)
- [Technologies used](#Technologiesused)
- [Features](#features)
- [File Structure](#FileStructure)
- [Getting started](#GettingStarted)
- [Setup & Installation](#Setup&Installation)
- [Notes](#Notes)
- [Example interaction](#Exampleinteraction)
- [License](#-license)
---
## About
This is a weather app project,where users can enter any city name to get the 5-day weather forecast or simply click on the “Use Current Location” button to get their current location’s weather details, including temperature, wind speed, humidity, and more. This project is also mobile-friendly, which means it looks great on all devices.weather app project allows you to apply your web development skills to a real-world application. Also, it helps you to better understand DOM manipulation, Event handling, CSS styling, APIs, and more.

## Project Plan

- **Search by City**: Users can search for weather information by entering a city name.
- **Displays Key Weather Data**: Shows temperature (in Celsius), humidity, wind speed, and weather description.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Weather Icon**: Displays weather icons based on the conditions (sun, rain, clouds, etc.).

## live Demo

You can view the live version of this weather app at:  
[https://disha14577.github.io/Minor-Project/](https://disha14577.github.io/Minor-Project/)

## Technologies used
- Front end Development ( Html , CSS ).
- Back end Development ( JavaScript ).
- Tester
- UI/UX Developer
- OpenWeatherMap API (for weather data)

## File Structure
- mausam.html
- style.css
- script.js
### Key Features:
- Users enter a city name in the input field.
- The app fetches data from the OpenWeatherMap API using the `fetch` method.
- The weather details (temperature, humidity, wind speed, etc.) are displayed on the page.
- If a city is not found, an error message is shown.

## Why I consider building a weather app?
-	Creating a weather website can be a fulfilling project that serves a broad audience. With the right set of tools and a well-thought-out approach, your website can become a go-to resource for weather information.
-	High Demand and Utility which means Weather websites are visited regularly, fostering repeat traffic.
-	building a weather app project allows you to apply your web development skills to a real-world application.
-	it helps you to better understand DOM manipulation, Event handling, CSS styling, APIs, and more.
-	Weather websites can generate revenue through ads, affiliate marketing, premium subscription services (like ad-free access or advanced data), or partnerships with businesses in travel, outdoor gear, or agriculture.
-	A weather website can foster an engaged community by offering localized features. Users may share updates, storm reports, or photos, helping to build trust and expand your platform organically.

## Steps To Create Weather App in HTML & JavaScript
### To create your weather app using HTML, CSS, and JavaScript, follow these step-by-step instructions:

Create a folder. You can name this folder whatever you want, and inside this folder, create the mentioned files.
Create an index.html file. The file name must be index and its extension .html
Create a style.css file. The file name must be style and its extension .css
Create a script.js file. The file name must be script and its extension .js

## Setup & Installation

You can easily set up this weather app locally by following these steps:

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari, Edge).
  
  

### Clone the repository (Optional)

If you want to clone the repository and run it locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
2. Open the `index.html` file in your browser.

   You don't need any server or backend for this app since it's fully frontend-based.
   
## Example interaction
User : "Delhi"
Weather app:"Delhi (2024-11-21)
Temperature: 25.06°C
Wind: 1.8 M/S
Humidity: 33%"


## LICENSE
This project is [MIT](./LICENSE) licensed. 

## 📝 Notes
your weather app is still unable to show the weather forecast for any location if you’ve not provided your OpenWeatherMap API key in the API_KEY variable. To get a free API key, sign up for an account at https://home.openweathermap.org/api_keys. Your API key may take minutes or hours to activate. You’ll get an error like “Invalid API Key” or something similar during this time.
   
## API Key

This app uses the **OpenWeatherMap API** to fetch weather data. If you're planning to use it for personal purposes or modifications, you may need to create your own API key by signing up at [OpenWeatherMap](https://openweathermap.org/api).

1. Once you have your key, you can replace the existing API key in the JavaScript file.


```javascript
const apikey = "YOUR_API_KEY_HERE"; // Replace this with your API key.




