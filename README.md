# Mapty — Workout Mapping App

A browser-based workout tracking application built while studying object-oriented programming (OOP) and modern JavaScript.

This project is based on Jonas Schmedtmann's JavaScript course and represents my learning and implementation practice.

## Live Demo

[Try Mapty App](https://sametbaltaa.github.io/mapty-app/)

*Allow location access in your browser to use the interactive map.*

## Features

- Add running and cycling workouts by selecting locations on a map
- Record distance, duration, cadence, and elevation gain
- Automatically calculate running pace (min/km) and cycling speed (km/h)
- Display workouts using interactive map markers
- Navigate to workout locations by selecting entries in the sidebar
- Save workout data using browser Local Storage
- Restore saved workouts when the application reloads

## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- Object-Oriented Programming (OOP)
- ES6 Classes and Class Inheritance
- Private Class Fields
- Leaflet.js
- OpenStreetMap
- Geolocation API
- Local Storage API

## What I Learned

- Structuring an application using object-oriented programming principles
- Creating reusable classes through inheritance
- Managing application state with private class fields
- Integrating a third-party mapping library (Leaflet.js)
- Working with browser APIs such as Geolocation and Local Storage
- Handling user interactions through DOM events
- Validating user input and calculating workout metrics

## Run Locally

1. Clone the repository.
2. Keep `index.html`, `script.js`, `style.css`, `logo.png`, and `icon.png` in the same directory.
3. Open the project using VS Code Live Server or another local HTTP server.
4. Allow location access in your browser.
5. Click anywhere on the map to add a workout.

Geolocation generally requires HTTPS or localhost. An internet connection is needed to load Leaflet and the map tiles.

Workout data is stored locally in the browser.

## Attribution

This educational project is based on **Jonas Schmedtmann's Mapty application** from *The Complete JavaScript Course*.

The original design and course materials belong to Jonas Schmedtmann. This repository demonstrates my implementation and understanding of the concepts taught during the course.

The portfolio version was reviewed and cleaned up, including corrections to workout calculations and removal of unnecessary debugging code.
