# 🌦️ Weather App

**Weather App** is a simple yet dynamic weather forecast application that delivers real-time weather data for any city in the world. Users get both daily and hourly forecasts, transforming raw data from the [OpenWeatherMap API](https://openweathermap.org/api) into clear, actionable insights — all through a clean and interactive interface.

![Screenshot of weather app](./doc/screenshot.png)

Built with HTML, CSS, and vanilla JavaScript, bundled with **Webpack** for optimised production builds. <br/><br/>
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)

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
- 📦 **Webpack bundled** - optimized for production
- 🎨 **Clean UI** - simple, focused interface for ease of use

## 🚀 Getting Started
**Prerequisites**
- Node.js (v14+)
- npx (comes with Node.js) 
- OpenWeatherMap API Key (free tier available)

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

3. Start the development server
```
npx webpack serve
```

4. Build for production
```
npx webpack
```

The optimised production build will be in the `/dist` folder.

## 🔮 Future Improvements
- [ ] Geolocation support - detect user location automatically
- [ ] Enhanced UI animations & transitions
- [ ] Cache recent searches using `localStorage`