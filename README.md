# Simple Weather Website

This is a simple, responsive web application built with React that displays the current weather for a given city.

## Features

- **Search by City:** Users can enter the name of any city to get its current weather information.
- **Current Weather Details:** The application displays key weather data including:
  - Temperature (in Celsius)
  - Humidity
  - Wind Speed
  - Weather Icon
- **Responsive Design:** The layout adapts to different screen sizes, providing a good user experience on both desktop and mobile devices.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **JavaScript (ES6+):** For the application's logic.
- **HTML5:** For the application's structure.
- **CSS3:** For styling the components.
- **OpenWeatherMap API:** This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch real-time weather data.
- **npm:** For package management.

## How to Set Up and Run

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/EmilliaSholaja/weather-app.git](https://github.com/EmilliaSholaja/weather-app.git)
    cd weather-app
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Get an API Key:**

    - Go to the [OpenWeatherMap website](https://openweathermap.org/).
    - Sign up for a free account.
    - Navigate to the "API keys" section to find your API key.

4.  **Configure the API Key:**

    - Create a `.env` file in the root directory of the project.
    - Add the following line to the file, replacing `"YOUR_API_KEY_HERE"` with the API key you obtained from OpenWeatherMap:
      ```bash
      REACT_APP_WEATHER_API_KEY=YOUR_API_KEY_HERE
      ```
    - **Note:** It's a best practice to keep API keys out of your code and use environment variables for security.

5.  **Run the application:**
    ```bash
    npm start
    ```
    The application will open in your default web browser at `http://localhost:3000`.

## Project Structure

- `src/`: Contains all the source code for the React application.
  - `components/`: (Optional) A directory for reusable React components (e.g., `Weather.jsx`).
  - `App.js`: The main component that renders the weather application.
  - `index.js`: The entry point for the React application.
- `public/`: Contains static assets like the `index.html` file and a manifest.

## Author

- Sholaja Emillia(https://github.com/EmilliaSholaja)

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
