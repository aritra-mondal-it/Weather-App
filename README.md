# Weather App - React

This is a simple weather application built using React. It allows users to search for a city and view the current weather conditions, including temperature, humidity, wind speed, and a brief description.

## Features

* **City Search:** Users can enter a city name to retrieve weather information.
* **Current Weather Display:** Displays temperature, humidity and wind speed.
* **Responsive Design:** It works well on various screen sizes.

## Technologies Used

* **React:** JavaScript library for building user interfaces.
* **OpenWeatherMap API:** For fetching weather data.
* **CSS :** For styling.
* **Axios/Fetch:** For making API requests.

## Prerequisites

* Node.js and npm (Node Package Manager) installed on your machine.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone <your-repository-url>
    cd weather-app
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Obtain an API key from OpenWeatherMap:**

    * Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/).
    * Generate an API key.

4.  **Create a `.env.local` file in the root directory:**

    * Add your API key to the `.env.local` file:

        ```
        REACT_APP_API_KEY=your_api_key_here
        ```

5.  **Start the development server:**

    ```bash
    npm start
    ```

    * The app will be available at `http://localhost:3000`.

## Building for Production

To create a production build:

```bash
npm run build
