# 🌤️ Simple Weather App

A clean, minimal, and responsive weather application built with HTML, CSS, and JavaScript that fetches real-time weather data from the OpenWeatherMap API.

## 🚀 Features

* **Current Weather:** Get up-to-date weather information for any city.
* **Search Functionality:** Easily search for a city using the input field (works with both the search button and pressing 'Enter').
* **Key Weather Details:** Displays:
    * Temperature (in Celsius)
    * Weather Description (e.g., "clear sky", "light rain")
    * Humidity (%)
    * Wind Speed (Km/H)
* **Dynamic Interface:** A welcoming start screen is replaced by the weather details once a search is performed.
* **Responsive Design:** The layout adapts smoothly to both desktop and mobile devices.

## 🛠️ Tech Stack

* **HTML5:** For the basic structure of the app.
* **CSS3:** For styling, layout, and responsiveness (using flexbox and media queries).
* **JavaScript (ES6+):** For DOM manipulation and fetching data from the API.
* **OpenWeatherMap API:** Used to source the live weather data.

## 📦 How to Run Locally

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
    *(Replace with your repository URL)*

2.  **Navigate to the project directory:**
    ```sh
    cd your-repository-name
    ```

3.  **Get your own API Key:**
    * Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up to get a free API key.
    * Open the `script.js` file.
    * Replace the placeholder value of the `apikey` constant with your new key:
        ```javascript
        const apikey = "YOUR_NEW_API_KEY_HERE";
        ```

4.  **Open the application:**
    * Simply open the `index.html` file in your web browser.

## Future Improvements

* Add weather icons that change based on the condition (e.g., sun, clouds, rain).
* Implement a 5-day forecast view.
* Add error handling for invalid city names or network issues.
* Include a toggle for Celsius and Fahrenheit units.
