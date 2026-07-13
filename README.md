A clean, modern, single-file React weather application that gives you real-time forecasts without dealing with API key setups.

Features
No API Key Needed: Uses the completely free Open-Meteo API for both location searching and weather data.

Smart Location Detection: Automatically asks for your location on launch. If denied, it defaults right to Mumbai, India.

Toggle Units: Switch between Celsius (°C) and Fahrenheit (°F) instantly.

Detailed Breakdown: Shows temperature, "feels like" temp, humidity, wind speeds/directions, UV index, and sunrise/sunset times.

Flexible Views: Switch between a 24-hour hourly scroll and a detailed 7-day forecast.

Built With
Frontend: React 18 & Babel (Loaded via CDN)

Styling: Vanilla CSS-in-JS (Flexbox, CSS Grid)

Data Sources: Open-Meteo Geocoding & Weather Forecast APIs

How to Run It Locally
Since everything is packaged in a single file, you don't need to run npm install or manage any node modules.

Clone this repository or download the HTML file.

Open the file directly in any modern web browser (like Chrome, Brave, Safari, or Firefox).

Start typing any city name in the search bar.

Project Structure
index.html — The entire codebase. Contains the foundational HTML setup, the UI layout styling, the core API logic, and the React application structure all in one place for quick deployments.
