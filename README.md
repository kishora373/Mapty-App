# Mapty-App
Welcome to the Mapty project! In this project, I built a workout logging application that allows users to track their running and cycling activities on an interactive map. The app integrates geolocation to automatically fetch the user's current position and displays it on a map using the Leaflet library. Additionally, it stores user data in the browser's localStorage so that workout logs persist across page reloads and sessions.
## Features
### Interactive Map: 
The map is rendered using the Leaflet library, and it shows workout markers for running and cycling activities.
### Geolocation: 
The app uses the browser’s geolocation API to automatically fetch the user’s location.
### Workout Input Form: 
A form to log running and cycling activities, including distance, time, and specific workout metrics like steps per minute or elevation gain.
### Dynamic Data Handling: 
The app dynamically updates the sidebar and the map with workout data.
### Data Persistence: 
Workout logs are stored in the browser's localStorage to persist data even after a page reload.
### Workout Navigation: 
The app allows users to click on a workout on the sidebar, which will automatically pan the map to the corresponding workout's location.

## Technologies Used
### JavaScript:
For building the app’s core functionality.
### Leaflet: 
A JavaScript library for displaying interactive maps.
### Geolocation API: 
For fetching the user's current location.
### localStorage: 
To persist workout data in the browser.

