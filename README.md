# Live Weather Viewing Application 

## About

Welcome to my live weather viewing application !
This is a static web-application that connects to OpenWeather API and displays live weather or 30 day forecast of over 200000 cities globally. 
This project is made using python programming language and flask web-framework. 

## Installations

- [Python](https://www.python.org/downloads/) v3.8.0 or greater
- [Flask](https://flask.palletsprojects.com/en/2.0.x/installation/#install-flask) (Python Version 3.7 or greater)

## Running on your local machine

1. Download this repository to your local machine. 

```
$ git clone https://github.com/Dhruvbam/Live_Weather_App
```

2. Open this folder in your terminal/cmd prompt and run the following code:
```
$ flask run
```
3. You should see a localhost server running, copy this address into any browser to begin.

## Set-up 

1. The landing page consists of a form that asks for city and scale details. 
2. Weather data is displayed after filling the form.
3. Weather data - Max/Min temp, current temp, freindly icon, weather description.
4. A quote unique to different weather types is also displayed.
5. A map is pulled from Open Steet API where as weather data is pulled from Open Weather API 
6. This is a freindly app that handles all common errors and redirects user to proper webpages. 
## Descriptions 

- ```app.py``` : Program entry point
- ```authentication.py``` : Makes requests to the OpenWeather API and returns json data in Python Dictionary Format.
- ```customDictionary.py``` :  This module creates a custom dictionary of data for different webpages.
- ```index.html & weather.html``` : Display dynamic data from form fields using POST Http request method.

## Refrences and Learning Outcomes

- Learning Outcomes 
    - Learned more about API requests, how to parse JSON data and manipulate it.
    - Learned more about HTML, CSS use with Jinja2 tools to parse variables to display dynammic data. 
    - Learned more about Python Web Application enviornment, HTTP Requests and authentication.
    - Learned more about Map Data from passing from in HTML and using JavaScript.

- OpenWeather API Documentation
    - https://openweathermap.org/current
    - https://openweathermap.org/api/forecast30

- Open Layers Maps API Documentation 
    - https://openlayers.org/en/latest/apidoc/

- Python & Flask 
    - https://flask.palletsprojects.com/en/2.0.x/tutorial/index.html
    - https://www.youtube.com/watch?v=Z1RJmh_OqeA&t=1917s

## Screenshots:
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm.jpg)
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm1.jpg)
![alt text](https://github.com/Dhruvbam/Live_Weather_App/blob/main/Live_Weather_App/images/wm2.jpg)
