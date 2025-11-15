# Live Weather Viewing Application 
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm1.jpg)

The Live Weather app is a Python and Flask based application that accesses the OpenWeather API to present real-time weather data and 30-day forecasts for over 200,000+ cities worldwide. The project features a dynamic, responsive UI, seamless integration with weather and map APIs, and robust error handling. Users can search by city, view temperatures, icons, friendly quotes, and global maps using OpenLayers. Designed for simple deployment and extensible code, this app demonstrates practical skills in API integration, Python web development, and user-centric design.

## Features & Technical Details

- **Global Coverage:** Live weather and 30-day forecasts for over 200,000 cities using OpenWeather API.
- **Real-Time Data:** Displays max/min temperature, current temp, weather icons, and custom weather quotes.
- **API Integration:** Combines OpenWeather (weather) and OpenLayers (map) APIs for robust and interactive data visualization.
- **Responsive UI:** Form-driven landing page enables city search, scale selection, and displays dynamic data.
- **Error Handling:** Gracefully manages missing/invalid cities, showing user-friendly redirects and info.
- **Modular Backend:** Built in Python and Flask, with clear separation of authentication, data handling, and view logic (`app.py`, `authentication.py`, `customDictionary.py`).
- **Frontend Tech:** Dynamic HTML/CSS (Jinja2 templates), user-friendly navigation supporting POST requests for updating weather data.
- **Learning Outcomes:** Strengthened skills in RESTful API requests, JSON parsing, Python web development, and interactive UI construction.



## Quick Setup

**Requirements:**  
- [Python](https://www.python.org/downloads/) 3.8+
- [Flask](https://flask.palletsprojects.com/en/2.0.x/installation/#install-flask)

**Getting Started:**
1. Clone the repo:  
   `git clone https://github.com/Dhruvbam/Live_Weather_App`
2. Run the app:  
   `flask run`
3. Visit the localhost link in your browser.

**Usage Highlights:**  
- Enter a city and choose units – instantly see current weather, forecast, maps, and a weather-based quote.
- Robust error handling and redirects enhance user experience.

**Key Files:**  
- `app.py` – Main web app
- `authentication.py` – API requests
- `customDictionary.py` – Page data dicts
- `index.html` / `weather.html` – Dynamic HTML templates


### Refrences 

- OpenWeather API Documentation
    - https://openweathermap.org/current
    - https://openweathermap.org/api/forecast30

- Open Layers Maps API Documentation 
    - https://openlayers.org/en/latest/apidoc/


## Screenshots:
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm.jpg)
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm1.jpg)
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm2.jpg)
