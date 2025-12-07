# Weather App

A simple, interactive weather application that displays real-time weather information for any city in the world.

## Features

- 🔍 **City Search**: Search for weather information by entering any city name
- 🌡️ **Temperature Display**: Shows current temperature in Celsius
- 💧 **Humidity Level**: Displays current humidity percentage
- 💨 **Wind Speed**: Shows wind speed in km/h
- 🌊 **Pressure**: Displays atmospheric pressure in hPa
- 👁️ **Visibility**: Shows visibility distance in kilometers
- 🤔 **Feels Like**: Displays the "feels like" temperature in Celsius
- 🎨 **Weather Icons**: Dynamic weather icons that change based on conditions
- ✅ **Error Handling**: Shows error message for invalid city names

## How It Works

1. Open `index.html` in your web browser
2. Enter a city name in the search box
3. Click the search button
4. The app will fetch real-time weather data from OpenWeatherMap API
5. Weather information will be displayed with appropriate weather icons

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling and gradient backgrounds
- **JavaScript**: Dynamic functionality and API integration
- **OpenWeatherMap API**: Real-time weather data

## Files Structure

```
weather/
├── index.html       # Main HTML file
├── style.css        # Styling and layout
├── script.js        # JavaScript functionality
├── README.md        # Project documentation
└── images/          # Weather icons and images
    ├── search.png
    ├── humidity.png
    ├── wind.png
    ├── pressure.png
    ├── visibility.png
    ├── feels_like.png
    ├── clouds.png
    ├── clear.png
    ├── drizzle.png
    └── rain.png
```

## Setup Instructions

1. Clone or download this project
2. Make sure all image files are present in the `images/` folder
3. Open `index.html` in your web browser
4. No additional installation or dependencies required

## Weather Conditions Supported

- ☁️ Clouds
- ☀️ Clear
- 🌧️ Drizzle
- 🌫️ Mist
- 🌧️ Rain

## API Information

This app uses the **OpenWeatherMap API** for weather data.

- **API Key**: e91c7ac76e15d08d87ad02aa5a470217
- **Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
- **Units**: Metric (Celsius, m/s, hPa)

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Features Overview

| Feature | Description |
|---------|-------------|
| Real-time Weather | Fetches current weather data from OpenWeatherMap |
| Multiple Metrics | Temperature, humidity, wind speed, pressure, visibility, feels like |
| Visual Feedback | Changes weather icons based on current conditions |
| Error Handling | Displays error message for invalid city names |
| Responsive Design | Works on desktop and mobile devices |

## Future Enhancements

- Add weather forecast for multiple days
- Add geolocation feature to auto-detect current city
- Add weather alerts and warnings
- Add favorite cities bookmark feature
- Dark mode toggle
- Multiple language support

## License

This project is open source and available for educational purposes.

## Author

Created as a weather application project.

## Support

For issues or questions, please check:
- Network connection is active
- City name is spelled correctly
- Images folder contains all required weather icons
