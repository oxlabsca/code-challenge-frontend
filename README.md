# Coding Challenge: Weather Dashboard

### Objective
Create a **Weather Dashboard** application where users can search for cities and view current weather details and a short-term forecast.

### Requirements

#### City Search
- Provide an input field for users to search for a city's weather information.
- Display the current weather data for the searched city.

#### Weather Details
- Show details for the selected city’s current weather, including:
  - Temperature
  - Weather description (e.g., Clear, Cloudy, Rain)
  - Humidity
  - Wind speed
- Display an icon representing the weather condition (e.g., a sun icon for clear weather).

#### Short-Term Forecast
- Display a forecast for the next 5 days, with the following details:
  - Date
  - Forecasted temperature (high and low)
  - Forecasted weather description
  - Weather icon for each day

#### Recent Searches
- Keep track of the last 3 cities searched and display them as recent searches.
- Allow users to click on a recently searched city to view its weather again.

#### Responsive Design
- Ensure the dashboard is responsive for both desktop and mobile screens.

### Additional Requirements
1. **API Integration**: Use a weather API, like [OpenWeatherMap](https://openweathermap.org/api) or any other open weather API (e.g., Weatherbit, MetaWeather). Make sure to use only publicly accessible data.
2. **State Management**: Use React’s `useState` or `useReducer` hooks to manage state.
3. **Styling**: Use CSS or a CSS-in-JS library (e.g., styled-components or Tailwind CSS) to create a modern, visually appealing design.
4. **Error Handling**: Show an error message if the user enters an invalid city name or if the API call fails.

### Guidelines
- **Time Limit**: You should be able to complete the challenge in **6 hours**.
- **Framework Choice**: You can use **React.js or Next.js**.
- **Focus Areas**:
  - API integration and handling asynchronous data
  - State management and data manipulation
  - Clean and modular component structure
  - Styling and responsiveness
  - Error handling

### Example API Data Structure
The weather API response might look like this (for current weather):

```json
{
  "name": "London",
  "main": {
    "temp": 15.0,
    "humidity": 80
  },
  "weather": [
    {
      "description": "clear sky",
      "icon": "01d"
    }
  ],
  "wind": {
    "speed": 4.6
  }
}
```

### **Submission Guidelines**

- Please submit a link to a public repository with your solution.
- Ensure all instructions are in `README.md` for setup and usage.
- Provide explanations for any unique design or architectural choices in your solution.

---

### Evaluation Criteria
This challenge will help evaluate a candidate’s ability to:

- Work with APIs and handle asynchronous data fetching
- Display and manage dynamic data from user inputs
- Organize components effectively with reusable code
- Handle errors gracefully and create a polished, responsive design

Good luck, and we look forward to reviewing your solution!