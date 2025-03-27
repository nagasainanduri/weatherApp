# Weather Detection App

## Overview

This is a web-based weather forecasting application that allows users to search for weather conditions by city name or automatically fetch their current location's weather. The app also integrates a real-time map using the MapTiler API to display the searched location.

## Features

- Search weather by city name.
- Automatically detect the user's location and fetch weather data.
- Display temperature, humidity, wind speed, pressure, and UV index.
- Interactive map displaying the selected location.
- Smooth loading animations for better user experience.
- Fully responsive design for different screen sizes.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **APIs:**
  - [Wttr.in API](https://wttr.in/) for weather data.
- **Libraries:**
  - [Leaflet.js](https://leafletjs.com/) for interactive maps.
  - Google Fonts (Poppins) for typography.

## Setup Instructions

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```
2. Open `index.html` in a web browser.
3. Ensure you have an active internet connection to fetch data from APIs.

## Structure

```
weather-app/
│── index.html   # Main HTML structure
│── style.css    # Styling and responsiveness
│── script.js    # JavaScript logic for fetching data and handling UI
```

## How It Works

1. The app loads a map centered at a default location.
2. Users can search for a city, and the app fetches weather data for that location.
3. If geolocation is enabled, the app automatically gets the user's location and displays relevant weather data.
4. The weather details and map update dynamically based on user input.

## Future Enhancements

- Improve performance with API request optimizations.
- Add more weather details like precipitation and visibility.
- Implement a dark mode.

## Credits

- **Weather Data:** Wttr.in API
- **Icons & Styles:** Google Fonts, Leaflet.js

