# FreightWise

This project is a solution to the FreightWise programming test, demonstrating API integration, error handling, and DOM manipulation using JavaScript, Axios, and Leaflet.js for interactive map rendering.

## Overview

The purpose of this project is to showcase the ability to:

- Make API calls using `axios` to fetch data from external services (like OpenWeatherMap).
- Perform DOM manipulation to display weather information in a user-friendly manner.
- Handle errors gracefully and inform the user when something goes wrong.
- Use modern JavaScript features, such as async/await, and third-party libraries effectively.

The project fetches current weather data for Brentwood, TN, or uses the browser’s geolocation feature to display weather data for the user’s current location. Additionally, the weather data is visually enhanced with a satellite map powered by Leaflet.js.

## Features

- **API Integration**: Uses OpenWeatherMap API to get current weather data.
- **Geolocation**: Utilizes the browser's Geolocation API to fetch the user's location and display relevant weather information.
- **Error Handling**: Displays error messages in a user-friendly way when data retrieval fails.
- **Interactive Map**: Renders a temperature-based satellite map using Leaflet.js and OpenWeatherMap's tile service.
- **Responsive Design**: Basic CSS to ensure readability and a pleasant user experience.

## Technologies Used

- **JavaScript (ES6)**: Modern JavaScript features and best practices.
- **Axios**: Chosen for making HTTP requests due to its ease of use and wide support.
- **Leaflet.js**: Used for rendering the map and weather overlays.
- **HTML/CSS**: Basic structure and styling for a clean UI.

## Getting Started

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nimkamp/freight-wise.git
   ```
