# wheatherApp

https://github.com/otabek98/wheatherApp/assets/78654682/ea74651b-09ca-4e96-8ce3-9a4f9da81691

## Weather Update App

This Android app provides real-time weather updates for a specified city and country. It utilizes the OpenWeatherMap API to fetch weather information and displays it on the user interface.

### Features

1. **Weather Information Retrieval:** The app allows users to input the city and country for which they want to obtain weather details.

2. **OpenWeatherMap API Integration:** It integrates with the OpenWeatherMap API to fetch real-time weather data.

3. **Display of Weather Details:** Upon a successful API response, the app extracts relevant weather details such as temperature, feels-like temperature, humidity, description, wind speed, cloudiness, and pressure. These details are then displayed on the user interface.

4. **AdMob Integration:** The app includes AdMob ads to generate revenue through ad displays.

### Usage Instructions

1. **Input City and Country:** Launch the app and input the desired city and country in the respective text fields.

2. **Fetch Weather Details:** Click the "Get Weather" button to initiate the process of fetching weather details for the specified location.

3. **View Weather Information:** The app displays the current weather information, including temperature, feels-like temperature, humidity, description, wind speed, cloudiness, and pressure.

### Code Overview

- **API Endpoint:** The OpenWeatherMap API endpoint is set as a constant (`url`) along with the API key (`appid`), which is required for making requests.

- **UI Elements:** The app's user interface includes EditText fields (`etCity` and `etCountry`) for user input, a TextView (`tvResult`) to display weather details, and an AdView (`mAdView`) to show advertisements.

- **Weather Details Retrieval:** The `getWeatherDetails` method is triggered when the user clicks the "Get Weather" button. It constructs the API URL based on user input, makes a request using Volley, and processes the API response to display relevant weather information.

- **AdMob Integration:** AdMob is initialized in the `onCreate` method, and an ad is loaded into the `AdView` (`mAdView`).

### Dependencies

- [Volley Library](https://developer.android.com/training/volley): Used for making network requests.
  
- [AdMob](https://developers.google.com/admob): Integrated for displaying advertisements.

### API Key

Ensure that the OpenWeatherMap API key (`appid`) is valid and up-to-date. Replace it in the code if necessary.

### Disclaimer

This app is dependent on the OpenWeatherMap API, and its functionality is subject to the availability and reliability of the API service. Users need a working internet connection for the app to fetch and display weather details.

### Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/): Provides the weather data used by the app.

- [AdMob](https://developers.google.com/admob): Enables in-app advertisements.

### Author

[Your Name]

### License

This project is licensed under the [MIT License](LICENSE).
