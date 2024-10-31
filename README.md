Weather App

This Java-based Weather App provides real-time weather information and forecasts for any city worldwide. The application features a user-friendly graphical interface and utilizes the OpenWeatherMap API to fetch weather data.

Features

-  Fetch and display the current weather conditions for a specified location.
-  Retrieve and display a 5-day weather forecast.
-  Keep track of previously searched locations.
-  Switch between Celsius and Fahrenheit.
-  The background color and icons change based on the time of day and current weather conditions.

 Getting Started

 Prerequisites

- Java Development Kit (JDK) installed (version 8 or higher recommended).
- An IDE (like IntelliJ IDEA, Eclipse, or NetBeans) for easier code management.
- Access to the OpenWeatherMap API with a valid API key. (Replace the placeholder key in the code.)

 Installation

1. Clone the Repository:
   git clone <repository-url>
   cd weatherapp
   

2. Set Up API Key:
   - Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).
   - Replace the placeholder API key in the WeatherAPI class:
     java
     private static final String weatherApiKey = "YOUR_API_KEY";
     

3. Compile and Run:
   - Compile the project and run the WeatherAppGUI class.

 Usage

1. Launch the application.
2. Enter a city name in the input field and click the "Search" button.
3. View the current weather and 5-day forecast displayed in the UI.
4. Use the temperature unit selector to switch between Celsius and Fahrenheit.

 Code Structure

- WeatherAPI.java: Contains methods to fetch current weather data and forecasts from the OpenWeatherMap API.
- SearchHistory.java: Manages the search history entries.
- WeatherAppGUI.java: Implements the graphical user interface, handles user interactions, and displays weather data.

 Libraries Used

- org.json: For handling JSON data received from the OpenWeatherMap API.
- javax.swing: For building the GUI components.
