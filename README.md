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
    git clone "https://github.com/aritra-mondal-it/Weather-App.git"
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
        VITE_APP_ID=your_api_key_here
        ```

5.  **Start the development server:**

    ```bash
    npm start
    ```

    * The app will be available at `http://localhost:<host_number>`.

## Building for Production

To create a production build:

```bash
npm run build
```

## Screenshots of the webpage

**1. Default Page -** When you open the webpage by default, it shows London's weather informatics.

<img src="https://github.com/aritra-mondal-it/Weather-App/blob/main/Screenshots/Default_page.png"/>

**2. New Page -** After you search any city name, it displays the weather information of that city.

<img src="https://github.com/aritra-mondal-it/Weather-App/blob/main/Screenshots/New_page.png"/>

## URL

You can visit the webpage by clicking on this link - [https://weather-app-aritra-mondal-ju-it.netlify.app/](https://weather-app-aritra-mondal-ju-it.netlify.app/)
