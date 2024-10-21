# Weatherly App


Web Systems and Technology Project | S3101 | MMDC


Zyra Joy Dongon & Claros Orcullo | BSIT



Weatherly App is a simple weather application that allows users to search for weather information by city name. 
The app provides temperature, humidity, and wind speed data using the OpenWeatherMap API.


##Project Structure

The project consists of the following main files and directories:

WeatherlyApp/

WeatherlyApp/ │ ├── images/ # Contains all images used in the app │ ├── clouds.png # Icon for cloudy weather │ ├── clear.png # Icon for clear weather │ ├── drizzle.png # Icon for drizzle weather │ ├── humidity.png # Icon representing humidity │ ├── mist.png # Icon for misty weather │ ├── rain.png # Icon for rainy weather │ ├── search.png # Icon for the search button │ ├── wind.png # Icon representing wind speed │ ├── style.css # The main CSS file for styling the application ├── index.html # The main HTML file that structures the application ├── README.md # This file explaining the project structure and how to run the app





# Key Files:
    - index.html: This file is the main entry point of the app. It contains the HTML structure and links to external CSS and JavaScript files.

    - style.css: This file contains all the styles used in the Weatherly App, such as layout, colors, fonts, and icons.

i   - mages/: This directory contains all the icons and images used in the app for different weather conditions (clouds, rain, clear skies, etc.).

# How to Run the Weatherly App

##To run the Weatherly App, follow these steps:

Prerequisites:

    - A web browser (Chrome, Firefox, etc.)
    - An active internet connection (to load external resources such as the API and fonts)
    - Basic knowledge of Git (if you're cloning from a repository)

Steps:

1. Clone the Repository (Optional): If you have Git installed and the repository URL, clone the project from GitHub:

    - git clone https://github.com/clarkorcullo/weatherlyappWSTFinal.git

2. Navigate to the Project Directory: Once the repository is cloned, or if you already have the files, open the project folder on your machine:

    - cd weatherlyappWSTFinal

3. Open the App: Open the index.html file in a web browser:

    - Right-click the index.html file and select Open With → Your browser (e.g., Chrome).

4. Search for a City:

    - In the app, enter the name of any city in the search box and click the search button.
    - The app will display the current weather conditions for that city, including temperature, humidity, and wind speed.


API Key:
The app uses the OpenWeatherMap API for fetching weather data. The API key is hardcoded in the JavaScript section of index.html. You can change the key if needed:

const apiKey = "2dc08288abcf65ff7d404cd89074a0c8";  // Replace with your own OpenWeatherMap API key


Troubleshooting:

- If you encounter any issues while running the app, check the following:

    1. Invalid City Name: If you enter a non-existent or incorrect city name, an error message will display below the search box.
    2. CORS Issue: If you're running the app locally and facing a CORS error while fetching data, consider using a browser extension that allows CORS or hosting the app on a simple web server.


