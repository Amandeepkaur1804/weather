# Introduction
This code creates a simple weather forecast web application. It allows users to input a city name and retrieve current weather information, including temperature, humidity, and wind speed, using the OpenWeatherMap API. The interface updates dynamically based on the weather conditions of the specified city.

# Features
1. City Weather Search: Users can input the name of any city to get its current weather information.

2. Real-time Weather Data: Retrieves and displays real-time weather data including temperature, humidity, and wind speed using the OpenWeatherMap API.

3. Dynamic Weather Icon: Updates the weather icon based on current weather conditions (e.g., clouds, clear, rain).

4. Error Handling: Displays an error message if an invalid city name is entered.

5. Responsive Design: The application is designed to be responsive, ensuring a good user experience on different devices.

# How to Use
1. Setup: Ensure you have an active internet connection. Obtain an API key from OpenWeatherMap by signing up.

2. Modify API Key: Replace the placeholder apiKey in the script with your actual API key from OpenWeatherMap.

3. Run the Application: Open the HTML file in a web browser.

4. Search for a City's Weather: Enter the name of a city in the input field. Click the search button or press enter.The application will display the current weather information for the specified city.

# Description
This weather forecast application is built using HTML, CSS, and JavaScript. Below is a brief overview of the key sections of the code:

HTML Structure: The HTML file sets up the basic structure, including input fields for city search and sections for displaying weather data.
It also includes references to external CSS for styling and internal JavaScript for functionality.

CSS Styling: The external CSS (weather.css) file contains styles to make the application visually appealing and responsive.

JavaScript Functionality: Uses the OpenWeatherMap API to fetch weather data.
1. checkWeather(city): An asynchronous function that fetches weather data for the specified city and updates the UI accordingly.
2. Handles errors by displaying an error message when an invalid city name is entered.
3. Listens for a click event on the search button to trigger the weather data fetch.
   
This code provides a functional and user-friendly weather forecast application, demonstrating how to integrate external APIs and update the user interface dynamically.

The initial interface of the web app 
![Screenshot (63)](https://github.com/Amandeepkaur1804/weather/assets/107187322/35e909d6-2529-4214-8f3e-5da78959b930)

Search after entering the location of the city 
![Screenshot (65)](https://github.com/Amandeepkaur1804/weather/assets/107187322/5bc62938-f5ae-447b-8da2-22c082b470af)

Invalid Entry Error

![Screenshot (66)](https://github.com/Amandeepkaur1804/weather/assets/107187322/813e0724-8356-4dc6-a4ba-bec0e134c628)

