
# Weather Application

A simple weather dashboard built with Flask that displays current weather conditions and a short-term forecast for a specified location. The app demonstrates backend development with Flask and frontend styling with HTML and CSS. It's designed to be visually appealing, with clean and modern weather cards.

## Features

- Display current temperature, location, and weather conditions.
- 3-hour weather forecast including icons for sun, clouds, and rain.
- Responsive and minimalistic design using custom CSS.
- Easy to extend with more features, like user preferences or location-based services.

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (custom styling)
- **Weather Data**: External API (OpenWeatherMap or any other)

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate into the project directory:

   ```bash
   cd weather-app
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   flask run
   ```

5. Open your web browser and go to `http://127.0.0.1:5000/weather` to see the weather dashboard.

## Folder Structure

```
/weather_app_project/
│
├── /static/
│   ├── styles.css
│   └── /icons/
│       ├── sun.png
│       ├── cloud.png
│       └── rain.png
│
├── /templates/
│   ├── layout.html
│   └── weather.html
│
├── app.py
└── requirements.txt
```

## Future Improvements

- Add location-based weather data fetching using user input.
- Show a 5-day forecast with more detailed hourly breakdowns.
- Save user preferences for favorite locations.
