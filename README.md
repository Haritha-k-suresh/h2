# WeatherYouLikeIt

**WeatherYouLikeIt** is a beginner-friendly project that provides weather-based outfit recommendations. It fetches real-time weather data for a user-specified city and suggests appropriate clothing options.

---

## Features
- **Real-Time Weather Information**: Fetches current weather data using the OpenWeatherMap API.
- **Outfit Recommendations**: Provides clothing suggestions based on the current temperature and weather conditions.
- **Responsive Design**: The user interface is mobile-friendly and works well on all devices.

---

## Technologies Used
- **HTML**: For structuring the application.
- **CSS**: For styling the interface.
- **JavaScript**: For fetching weather data and dynamically updating the content.
- **OpenWeatherMap API**: To retrieve real-time weather data.

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/WeatherYouLikeIt.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd WeatherYouLikeIt
   ```

3. **API Key**:
   - Sign up at [OpenWeatherMap](https://openweathermap.org/) to get your free API key.
   - Replace the placeholder API key in the script (`const API_KEY = "6276aa122418a62924c00f1de10846db"`) with your own API key.

4. **Run the Application**:
   - Open `index.html` in your browser.

---

## How It Works
1. The user enters the name of their city into the input field.
2. The application fetches the current weather data for the city using the OpenWeatherMap API.
3. Based on the temperature and weather conditions, an appropriate outfit recommendation is displayed.

---

## Folder Structure
```
WeatherYouLikeIt/
├── index.html      # Main HTML file
├── style.css       # Inline styles (can be separated for modularity)
├── script.js       # JavaScript logic for fetching data and rendering content
```

---

## Future Improvements
- Add support for multiple languages.
- Display weather icons for better visuals.
- Save the last searched city and display its weather upon reloading.
- Expand outfit recommendations for specific conditions (e.g., snow, thunderstorms).

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments
- [OpenWeatherMap API](https://openweathermap.org/) for providing weather data.
- Inspiration for project development from beginner-friendly ideas.
