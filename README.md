# Weather App

A simple weather application built with **React (Vite)**, **HTML**, and **CSS** that fetches real-time weather data from the **OpenWeatherMap API**. The app allows users to search for a city's weather conditions, including temperature, humidity, and wind speed, and displays appropriate weather icons (clear, cloudy, rainy, etc.). Error handling is implemented to alert users if the city name is invalid or if there’s an issue with fetching data.

## Features

- **Real-Time Weather Data**: Fetches and displays weather information including temperature, humidity, and wind speed.
- **Weather Condition Icons**: Shows visual icons to represent the current weather conditions (e.g., cloudy, clear, rainy).
- **Search Functionality**: Users can search for the weather conditions of any city by entering its name in the search bar.
- **Error Handling**: Alerts users if an invalid city name is entered or if there’s an issue with fetching data from the API.

## Technologies Used

- **Vite**: As the build tool for a fast and optimized development environment.
- **React**: For building the UI and managing component states.
- **HTML**: For structuring the web page.
- **CSS**: For styling the app and ensuring a responsive design.
- **OpenWeatherMap API**: To retrieve real-time weather data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
2. Navigate to the project directory:
   ```bash
   cd weather-app
3. Install the necessary dependencies:
   ```bash
   npm install
4. Create a `.env` file in the root directory and add your **OpenWeatherMap API** key:
   ```bash
   VITE_APP_ID="your_openweathermap_api_key"
5. Run the app:
   ```bash
   npm run dev
6. Open your browser and navigate to:
   ```bash
   http://localhost:5173

## Usage

1. Enter the name of the city in the search bar.
2. View the current weather, including:
   - Temperature
   - Humidity
   - Wind speed
   - A weather icon showing the condition (e.g., clear, cloudy, rainy, etc.)
3. If an invalid city is entered or an error occurs during data fetch, an alert will be displayed.

## API Reference

This app uses the [OpenWeatherMap API](https://openweathermap.org/api). You need to sign up for a free API key and use it in the project.

## Contributing

Feel free to fork this repository, submit issues, or contribute by opening pull requests.

## License

This project is licensed under the MIT License.
