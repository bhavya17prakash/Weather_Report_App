
# Weather App using OpenWeather API

A weather application built with React for the frontend and Node.js with Express for the backend, utilizing the OpenWeather API to fetch hourly and daily weather forecasts.

## Features

- **Current Weather**: Display current weather conditions based on user location.
- **Hourly Forecast**: Show hourly weather data for the next 5 days.
- **Daily Forecast**: Provide daily weather data for the next 5 days.

## Technologies Used

- **Frontend**:
  - React <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png" alt="React" width="50">
  - Axios (for API requests)
  - Bootstrap or Material-UI (for styling)

- **API**:
  - OpenWeather API (for weather data)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather_report_app
   ```

2. **Setup Environment Variables**:

   Create a `.env` file in the root of the backend directory (`server/.env`) and add your OpenWeather API key:

   ```bash
   OPENWEATHER_API_KEY=your_api_key_here
   ```

3. **Install Dependencies**:

   ```bash
   # Install backend dependencies
   
   npm install

   ```

4. **Start the Application**:

   ```bash
   npm start

5. **Access the Application**:

   Open your web browser and go to `http://localhost:3000` to view the weather app.

## API Integration

- Ensure your OpenWeather API key is correctly set in the backend `.env` file.
