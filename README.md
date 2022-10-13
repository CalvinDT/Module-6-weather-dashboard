Server-Side APIs Challenge: Weather Dashboard
Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.

Use the 5 Day Weather ForecastLinks to an external site. to retrieve weather data for cities. The base URL should look like the following: https://api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon}&appid={API key}. After registering for a new API key, you may need to wait up to 2 hours for that API key to activate.

Description
When a valid city name is entered, the name is saved as part of a search history list and can be clicked on again to access the same data. The last search is saved to local storage so that it can be displayed when the page is reloaded. This dashboard is meant for travelers who want to plan ahead for the upcoming weather in different cities. https://github.com/CalvinDT/Module-6-weather-dashboard

User Story
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
Acceptance Criteria
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history

WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index

WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe

WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity

WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city

WHEN I open the weather dashboard
THEN I am presented with the last searched city forecast
The following image demonstrates the application functionality:

weather dashboard demo

Review
You are required to submit the following for review:

The URL of the deployed application.

The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

