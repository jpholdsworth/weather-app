# 🌦️ Weather App

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)

**Weather App** is a simple yet dynamic weather forecast application that delivers real-time weather data for any city in the world. Users get both daily and hourly forecasts, transforming raw data from the [OpenWeatherMap API](https://openweathermap.org/api) into clear, actionable insights — all through a clean and interactive interface.

Built with HTML, CSS, and vanilla JavaScript, bundled with **Webpack** for optimised production builds.

![Screenshot of weather app](./doc/screenshot.png)

## 📑 Table of Contents
- [The Vision](#-the-vision)
- [Features](#-features)
- [UI/UX](#-uiux)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Future Improvements](#-future-improvements)

## 🎯 The Vision
Most weather apps are cluttered. This project focuses on minimalism and context. The UI isn't just a skin; it's designed to adapt:
- Data Hierarchy: Crucial stats (temperature and condition) are prioritised, while secondary data (humidity and wind speed) is accessible but non-intrusive.
- Zero Bloat: No heavy frameworks. Just optimised, vanilla JavaScript for near-instant load times.

## 🎨 UI/UX 
A strong UI is crucial for building engaging applications. The Weather App is thoughtfully designed to provide users with accurate weather information while delivering a pleasant experience:

- **Desert landscape background** - evokes calm, warmth, and an inviting atmosphere
- **Typography and color palette** - chosen for readability and visual harmony
- **Weather icons** - provide instant visual cues so users can understand conditions at a glance

The combination of visual appeal and clarity makes the app intuitive and engaging.

## ✨ Features
- 🔍 **Search by city** - get real-time weather for any city worldwide
- 🌡️ **Current conditions** - temperature, humidity, wind speed, and overall weather
- 🌤️ **Dynamic weather icons** - reflect real-time conditions at a glance
- ⏱️ **Hourly forecast** - hour-by-hour breakdown for the current day
- 📅 **5-day forecast** - overview of the week ahead
- 🔄 **Unit toggle** - switch between °C/°F and metric/imperial for wind speed
- 🕐 **Time format toggle** - 12-hour or 24-hour time display
- ⚡ **Fast & lightweight** - vanilla JavaScript only, no frameworks
- 📦 **Webpack bundled** - optimised for production
- 🎨 **Clean UI** - simple, focused interface for ease of use

## 🚀 Getting Started
**Prerequisites**
- Node.js (v14+)
- npx (comes with Node.js) 
- API Key from
    - [OpenWeatherMap](https://openweathermap.org/api) (free tier available)
    - [WeatherAPI](https://www.weatherapi.com/) (free tier available)

### Installation & Setup
1. Clone the repository
```
git clone https://github.com/jpholdsworth/weather-app.git
cd weather-app
```

2. Install dependencies
```
npm install
```

3. Environment Configuration
Create a `.env` file in the root directory to protect your API keys:
- [OpenWeatherMap](https://openweathermap.org/api)
- [WeatherAPI](https://www.weatherapi.com/)

```
OPENWEATHER_API_KEY=your_key_here
WEATHER_API_KEY=your_second_key_here
```

> [!WARNING]
> Never commit your `.env` file.
> Ensure `.env` is included in `.gitignore`

4. Start the development server
```
npx webpack serve
```

5. Build for production
```
npx webpack
```

The optimised production build will be in the `/dist` folder.

## ⚡Usage
1. Open the app in your browser (localhost during dev or deployed site).
2. Enter a city in the search bar.
3. View current weather, hourly forecast, and 5-day forecast.
4. Toggle units (°C/°F), wind speed metric/imperial, and time format. 

## 🛠️ Tech Stack
- **HTML5** - semantic structure
- **CSS3** - minimalistic layout and styling
- **JavaScript (ES6+)** - application logic and API handling
- **Webpack** - module bundling and production optimisation

## 🧠 Architecture
The application follows a modular JavaScript structure to keep logic separated and maintainable:

- **index.js** - application entry point, state management, and event handling
- **current_weather.js** - fetches and renders current weather data
- **weather_forecast.js** - handles forecast API requests and data coordination
- **daily_forecast.js** - renders 5-day forecast UI
- **hourly_forecast.js** - renders hourly forecast UI
- **form.js** - input validation and error handling
- **footer.js** - dynamically updates footer content

Webpack bundles all modules into an optimised production build for efficient loading.

## 🧩 Development Principles
- **Modular design** - each feature isolated into focused modules
- **Separation of concerns** - API logic, UI rendering, and validation handled independently
- **Performance-first** - no frameworks, minimal bundle size
- **Maintainability** - reusable formatting utilities and clear data flow

## 🔮 Future Improvements
- [ ] Geolocation support - detect user location automatically
- [ ] Enhanced UI animations & transitions
- [ ] Cache recent searches using `localStorage`

---

Made with ❤️ using vanilla JavaScript.
