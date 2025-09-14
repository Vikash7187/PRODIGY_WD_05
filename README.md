# Weather App

A modern and responsive **Weather Application** that allows users to check real-time weather data for any city or their current location. The app displays current weather conditions, temperature, humidity, wind speed, visibility, pressure, UV index, cloud cover, and a 24-hour forecast.

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [File Structure](#file-structure)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Live Demo](#live-demo)  
- [Credits](#credits)  

---

## Overview

The Weather App is a **front-end web application** designed to provide real-time weather updates. Users can:

- Search for a city manually or use their current location  
- View temperature, "feels like", weather description, and icon  
- See additional details like humidity, wind speed, visibility, pressure, UV index, and cloud cover  
- Check a **24-hour weather forecast**  
- Handle errors gracefully when location or data retrieval fails  

The app is mobile-friendly and uses clean and modern UI design with Font Awesome icons.

---

## Features

- **City search:** Users can enter a city name to fetch weather data  
- **Current location detection:** Fetch weather for the user’s GPS location  
- **Real-time weather info:** Temperature, feels like, description, humidity, wind speed, visibility, pressure, UV index, cloud cover  
- **24-hour forecast:** Hourly weather updates with icons and temperature  
- **Error handling:** Displays error message if data cannot be fetched  
- **Loading state:** Spinner while fetching data  

---

## Technologies Used

- **HTML5** – Webpage structure  
- **CSS3** – Styling and responsive design  
- **JavaScript (ES6)** – API calls, DOM manipulation, and interactive functionality  
- **Font Awesome** – Weather and UI icons  
- **OpenWeatherMap API** – Weather data provider  

---

## File Structure

Weather-App/
│
├── index.html # Main HTML file
├── style.css # Styling
├── script.js # JavaScript functionality
├── sw.js # Service worker for caching (optional)
├── README.md # Project documentation

---

## Installation

1. Clone this repository:  

```bash
git clone <repository-url>

