# React Weather App
<img width="802" alt="Screenshot 2024-11-03 at 8 21 20 PM" src="https://github.com/user-attachments/assets/0fda69af-745e-47ae-affa-47b85381f905">

## About Project
Interactive weather app displaying real-time data. Built with React, Javascript, HTML, CSS, and OpenWeatherMap API. 

## Instructions
To search for a city, type the city name in the search bar and click the search button (🔍). (Note: Pressing ‘Enter’ to search is not yet enabled.)

## Live Demo
https://cm-react-weather-app.netlify.app

## Weather App Features:
- Displays current temperature, humidity, and wind speed.
- Supports over 10,000 cities with real-time updates.
- Provides real-time error handling for invalid city names.

## Technical Challenges & Learning Points
### Asynchronous Data Fetching with React:
- Implemented useEffect and async/await to fetch real-time weather data from the OpenWeatherMap API, handling async operations within React components. This was a valuable experience in managing side effects in React.

### Error Handling for User Input:
- Added error handling to account for invalid city names or API request failures, providing feedback to users when inputs are misspelled or network issues arise. This challenge emphasized the importance of a smooth user experience.

### Dynamic Styling Based on Weather Conditions:
- Dynamically updated icons and styles based on weather conditions (e.g., sun, rain) to create a more engaging, intuitive interface. This required handling conditional rendering effectively within React.
