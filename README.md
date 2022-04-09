# weather-dashboard


![License Badge](https://img.shields.io/github/license/mmeii/weather-dashboard) ![Top Language](https://img.shields.io/github/languages/top/mmeii/weather-dashboard)

This is a weather dashboard with form inputs that will run in the browser and feature dynamically updated HTML and CSS. 
It allows the user to search to view weather outlook for multiple cities. Suitable for travel or events planning. 

[OpenWeather API](https://openweathermap.org/api) is used to retrieve weather data for cities. And `localStorage` and `setItem()` is used to store persistent data.
`JSON.stringify()` is used to stringfiy the searched cities so it can be printed via `console.log` command. 

## Installation

1. Download or clone repository
2. Open the main page (index.html) on your browser to view
3. Use a text editor to view all coding. I'm using Visual Studio Code. 

## Functionality

- When searching for a city, the current and future conditions for that city will be displayed and that city will be added to the search history. 
  
- When viewing current weather conditions for the city, the following is displayed:
  * City name
  * Date
  * An icon representation of weather conditions
  * Temperature
  * Humidity
  * Wind speed
  * UV index
  
* When viewing the UV index, it is presented with a color indicating severity (reference: [Ultraviolet Index Wikipeadia](https://en.wikipedia.org/wiki/Ultraviolet_index#:~:text=A%20UV%20index%20reading%20of,broad%20spectrum%20SPF%2030%2B%20sunscreen.&text=A%20UV%20index%20reading%20of%206%20to%207%20means%20high,harm%20from%20unprotected%20sun%20exposure.))
  * ![#3EA72D](https://via.placeholder.com/15/3EA72D/000000?text=+) 0-2 Low
  * ![#FFF300](https://via.placeholder.com/15/FFF300/000000?text=+) 3-5 Moderate
  * ![#F18B00](https://via.placeholder.com/15/F18B00/000000?text=+) 6-7 Orange
  * ![#E53210](https://via.placeholder.com/15/E53210/000000?text=+) 8-10 Very High
  * ![#B567A4](https://via.placeholder.com/15/B567A4/000000?text=+) 11+ Extreme
  
* When viewing the future weather conditions for the city, a 5-day forecast will be displayed with the following information:
  * Date
  * An icon representation of weather conditions
  * Temperature
  * Humidity
  
* When hovering over the `search` button or the searched cities on the search history list, there will be a pointer cursor that helps users to be know that they can click on the searched city to view the weather conditions. 
* When a city in the search history is `clicked`, the current and future conditions for that city will display again. \
* When hitting the `enter` button, the current and future conditions for that city will also be displayed.
* When the weather dashboard browser is reloaded or opened, the last searched city forecast is displayed

  
## Features

* HTML
* CSS
* Bootstrap
* jQuery
* Moment.js
* Server-Side API - OpenWeather API
* Font Awesome Icon 

## Demo

![Weather Dashboard Demo](https://media.giphy.com/media/rDMHCL1P97Mimvs7b6/giphy.gif)

## Websites

* [Github](https://github.com/chaunnybby7/weather-dashboard)
* [Deployed](https://chaunnybby7.github.io/weather-dashboard/)

## License

  Copyright (c) YiLin Ong. All rights reserved.
  
  Licensed under the [MIT](LICENSE) license.