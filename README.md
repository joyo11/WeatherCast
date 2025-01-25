# WeatherCast

## Overview
WeatherCast is a modern iOS weather application built with SwiftUI that provides real-time weather information and forecasts for multiple cities worldwide. The app features a clean, intuitive interface with smooth animations and supports both light and dark themes. Users can track weather conditions for multiple locations, view detailed forecasts, and get current location weather updates.

## Features
- **Real-Time Weather Data**: Get current weather conditions including temperature, humidity, and wind speed
- **5-Day Forecast**: View extended weather forecasts for better planning
- **Multiple Cities**: Track weather for multiple locations worldwide
- **Location Services**: Get weather updates for your current location
- **Theme Support**: Choose between light, dark, or system theme
- **Temperature Units**: Toggle between Celsius and Fahrenheit
- **Animated UI**: Smooth transitions and weather animations
- **City Management**: Add and remove cities from your tracking list

## Technologies Used
- **SwiftUI**: Modern declarative UI framework for iOS
- **CoreLocation**: Location services for current weather
- **OpenWeatherMap API**: Weather data provider
- **Async/Await**: Modern concurrency for network calls
- **Environment Objects**: State management across views
- **Combine**: Data binding and state management

## Prerequisites
- Xcode 15.0+
- iOS 17.0+
- OpenWeatherMap API key
- Swift 5.9+

## Setup
1. Clone the Repository

```bash
git clone https://github.com/yourusername/WeatherCast.git

```


2. Install Dependencies
- Open the project in Xcode
- Wait for package dependencies to resolve

3. Configure API Key
- Replace `apiKey` in `WeatherService.swift` with your OpenWeatherMap API key

## Code Structure

### Views
- `ContentView.swift`: Main view with welcome screen and navigation
- `WeatherListView.swift`: List of cities and their weather
- `WeatherDetailView.swift`: Detailed weather information
- `WeatherCardView.swift`: Reusable weather card component

### Models
- `Weather.swift`: Core weather data model
- `WeatherResponse.swift`: API response model
- `Settings.swift`: App settings and preferences

### Services
- `WeatherService.swift`: API communication and data fetching
- `LocationManager.swift`: Location services handling

## Features in Detail
1. **Welcome Screen**
   - Animated weather icon
   - Feature highlights
   - Smooth transition to weather list

2. **Weather List**
   - Current location weather
   - Multiple city support
   - Swipe to delete cities
   - Pull to refresh

3. **Weather Details**
   - Current conditions
   - Temperature range
   - 5-day forecast
   - Additional weather metrics

## Contact
For any questions or inquiries, feel free to reach out:
- Email: shafay11august@gmail.com

## Notes
This project demonstrates modern iOS development practices using SwiftUI. Future enhancements could include:
- Weather notifications and alerts
- Weather widgets
- More detailed hourly forecasts
- Weather maps integration
- Historical weather data
- Weather sharing capabilities

## License
Copyright (c) 2025 Mohammad Shafay Joyo
