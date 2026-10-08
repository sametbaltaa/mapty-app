# Mapty — Workout Mapping App

A browser-based workout tracker built while following **Jonas Schmedtmann’s JavaScript course**. This is a learning project, not an original product concept. The implementation was reviewed and cleaned up for this portfolio repository.

## Features

- Add running or cycling workouts by selecting a location on the map
- Record distance and duration, plus cadence for runs or elevation gain for rides
- Calculate running pace (min/km) and cycling speed (km/h)
- View workouts as map markers and in a sidebar list
- Click a saved workout to move the map to its location
- Persist workouts in browser Local Storage

## Technologies

- HTML, CSS, and vanilla JavaScript (ES6+ classes, inheritance, private fields)
- Leaflet.js and OpenStreetMap tiles
- Browser Geolocation API and Local Storage

## Run locally

1. Keep `index.html`, `script.js`, `style.css`, `logo.png`, and `icon.png` in the same directory.
2. Open the directory using VS Code Live Server, or run a local HTTP server.
3. Allow location access in your browser, then click the map to record a workout.

Geolocation generally requires a secure context (HTTPS or localhost). An internet connection is required to load Leaflet and map tiles. Data stays in your browser.

## Attribution

This educational project is based on **Jonas Schmedtmann’s Mapty app** from *The Complete JavaScript Course*. Original course authorship and attribution are preserved in the application. It is presented here as coursework and practice, not as an independently conceived app.
