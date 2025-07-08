API: 
Weather API: https://www.weatherapi.com/docs/
const baseUrl = "http://api.weatherapi.com/v1";

Used Windy API to display the map forecast. 
Need the leaflet and windy API library to display map.
  <script src="https://unpkg.com/leaflet@1.4.0/dist/leaflet.js"></script>
  <script src="https://api.windy.com/assets/map-forecast/libBoot.js"></script>

Description:
1. Enter a city name in the form.
2. Choose to display the temperature in °C or °F (toggle switch). 
3. Click "Get Weather".
4. Click on 5 day or 10 day forecast button to see the forecast for the next 5 or 10 days. 

Index Page:
- There is validation feedback when entering the city's name (only letters can be entered). 
- There is a clear button to clear the city name from the form.
- An alert is displayed if the city name is blank.
- The background color changes when you hover on the list item on the index page. 
- The windy map appears when the city name is entered correctly.

Forecast Pages:
- The 10 day forecast can be filtered to display the temperatures less than or greater than
  a temperature entered by the user.
- The filter can be reset to display the 10 day forecast.
- The font is bold when you hover on the buttons (weather today, 5 day, and 10 day).