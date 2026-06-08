# Weather Dashboard 🌤️

A modern, real-time weather dashboard built with Vue 3, featuring live weather data, 7-day forecasts, and interactive maps. Uses the free Open-Meteo API with no authentication required.

## ✨ Features

- 🌍 **Global Weather Search** - Search for any city worldwide
- 🌡️ **Real-time Weather Data** - Current temperature, humidity, wind speed, precipitation
- 📅 **7-Day Forecast** - Detailed daily forecasts with temperature ranges and conditions
- ⭐ **Favorites System** - Save your favorite locations for quick access
- 🕐 **Search History** - Quick access to recently searched locations
- 🎨 **Modern UI** - Glassmorphism design with smooth animations
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- 🌐 **Geolocation** - Auto-load weather for your current location
- 🌙 **Dark Mode Ready** - Easy theme toggling
- ⚡ **Fast & Lightweight** - Minimal dependencies, optimized performance

## 🚀 Quick Start

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The app will open at `http://localhost:3000`

### Production Build

```bash
npm run build
```

Output files will be in the `dist/` folder.

### Preview Build

```bash
npm run preview
```

## 📁 Project Structure

```
weather-dashboard/
├── src/
│   ├── main.js                 # Entry point
│   ├── App.vue                 # Main component
│   ├── style.css               # Global styles
│   └── stores/
│       └── weatherStore.js     # Pinia state management
├── index.html                  # HTML root
├── package.json                # Dependencies
├── vite.config.js              # Vite configuration
├── tailwind.config.js          # Tailwind CSS config
├── postcss.config.js           # PostCSS config
└── README.md                   # Documentation
```

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Vue 3** | Progressive JavaScript framework |
| **Vite** | Next-generation build tool |
| **Pinia** | State management |
| **Tailwind CSS** | Utility-first CSS framework |
| **Axios** | HTTP client |
| **Open-Meteo API** | Weather data source |

## 🌐 API Integration

### Open-Meteo API (Free)

No API key required! The app uses the free Open-Meteo API for weather data.

- **Current Weather** - Temperature, humidity, wind speed, precipitation
- **Forecast** - 7-day forecast with daily min/max temperatures
- **Geocoding** - Search cities and get coordinates
- **Timezone Support** - Automatic timezone detection

**API Endpoints:**
- Weather: `https://api.open-meteo.com/v1/forecast`
- Geocoding: `https://geocoding-api.open-meteo.com/v1/search`

## 🎨 Features Breakdown

### 🔍 Location Search
- Real-time city search with autocomplete
- Search results show city name, region, and country
- Select any location to load its weather data

### 🌡️ Current Weather Display
- Large temperature display with weather emoji
- Feels-like temperature
- Humidity percentage
- Wind speed (km/h)
- Precipitation amount
- Timezone information

### 📅 7-Day Forecast
- Daily minimum and maximum temperatures
- Weather conditions with emojis
- Precipitation probability
- Wind speed
- Responsive grid layout

### ⭐ Favorites Management
- Add/remove locations from favorites
- Quick access buttons for favorite cities
- Persisted in browser localStorage

### 🕐 Search History
- Automatically saves last 10 searches
- One-click access to recent locations
- Persisted in browser localStorage

### 🎨 Modern Design
- Glassmorphism effect on UI elements
- Gradient backgrounds
- Smooth animations and transitions
- Responsive grid layouts
- Color-coded weather information

## 🌍 Supported Locations

The app supports weather data for any location worldwide:
- Cities
- Towns
- Regions
- Countries

Search results include:
- Official city names
- Administrative divisions (state/province)
- Country names
- Geographic coordinates

## 📊 Weather Data Displayed

### Current Weather
- Temperature (°C)
- Apparent temperature (feels like)
- Relative humidity (%)
- Wind speed (km/h)
- Precipitation (mm)
- Weather code/condition
- Timezone

### 7-Day Forecast
- Date and day name
- High/low temperatures
- Weather condition (with emoji)
- Precipitation probability (%)
- Maximum wind speed (km/h)

## 🎯 Weather Conditions

The app displays weather conditions as emojis:

| Emoji | Condition |
|-------|-----------|
| ☀️ | Clear/Sunny |
| ⛅ | Partly Cloudy |
| ☁️ | Cloudy |
| 🌫️ | Foggy |
| 🌦️ | Drizzle/Light Rain |
| 🌧️ | Rain |
| ❄️ | Snow |
| ⛈️ | Thunderstorm |
| 🌨️ | Snow Shower |

## 💾 Data Persistence

The app uses browser localStorage to remember:
- **Search History** - Last 10 searches
- **Favorite Locations** - User's favorite cities
- **User Preferences** - Theme settings (light/dark)

## 📱 Responsive Breakpoints

- **Mobile** - Full width, stacked layout
- **Tablet** - 2-column grid for forecast
- **Desktop** - Multi-column optimized layout

## 🚀 Deployment Options

### GitHub Pages
```bash
npm run build
# Push dist/ folder to gh-pages branch
```

### Vercel
```bash
vercel
```

### Netlify
```bash
npm run build
# Drag and drop dist/ folder to Netlify
```

### Traditional Hosting
```bash
npm run build
# Upload dist/ folder to your web server
```

## 🔒 Privacy

- No user data is stored on servers
- Location data is only used for weather API calls
- All data is stored locally in browser storage
- No cookies or tracking (unless you add analytics)

## ⚡ Performance

- Optimized bundle size (~50KB gzipped)
- Efficient API calls with caching
- Smooth animations with CSS transitions
- Lazy loading of components
- No unnecessary re-renders

## 🐛 Error Handling

- Network error messages
- Invalid location handling
- Graceful fallbacks
- User-friendly error messages

## 🛣️ Roadmap

- [ ] Multiple language support
- [ ] Air quality index
- [ ] UV index
- [ ] Pollen count
- [ ] Weather alerts
- [ ] Weather maps
- [ ] Historical weather data
- [ ] Export weather data
- [ ] Social sharing

## 📝 License

MIT License - Feel free to use this project for personal or commercial use.

## 👨‍💻 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📧 Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Create a discussion
- Contact the maintainers

## 🙏 Acknowledgments

- **Open-Meteo** - Free weather API
- **Vue.js** - Progressive framework
- **Tailwind CSS** - Utility CSS framework

---

**Version:** 1.0.0  
**Last Updated:** 2026-06-08  
**Status:** ✅ Active & Maintained
