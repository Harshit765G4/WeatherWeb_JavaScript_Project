# 🌦️ Weather Web – JavaScript Project

A simple and responsive weather application interface built with **HTML and CSS**, designed as a foundation for a JavaScript-powered weather dashboard.

The project currently provides a clean weather-card UI with a city search field, temperature display, weather condition icon, humidity, and wind-speed information. Weather values are currently represented as static content in the HTML and are ready to be connected to a weather API using JavaScript.

---

## ✨ Features

- 🔎 City search input
- 🌡️ Temperature display
- 🌧️ Weather condition illustration
- 💧 Humidity information
- 💨 Wind-speed information
- 📱 Responsive layout for different screen sizes
- 🎨 Gradient weather-card design
- 🖼️ Weather icons for multiple conditions

---

## 🛠️ Tech Stack

- **HTML5** – Application structure
- **CSS3** – Styling and responsive layout
- **JavaScript** – Intended for dynamic weather functionality
- **Image assets** – Weather and UI icons

> **Current status:** The repository currently contains the HTML/CSS interface and image assets. A JavaScript file and live weather API integration are not currently included.

---

## 🎯 Current Interface

The weather card contains:

- A search field for entering a city name
- Search button
- Weather condition icon
- Temperature
- City name
- Humidity
- Wind speed

The default UI currently displays example values such as:

```text
Temperature: 22°C
City: New Delhi
Humidity: 50%
Wind Speed: 15 Km/h
```

These values are static placeholders in the current implementation.

---

## 📁 Project Structure

```text
WeatherWeb_JavaScript_Project/
│
├── index.html
├── style.css
├── weather-app-img/
│   └── images/
│       ├── clear.png
│       ├── clouds.png
│       ├── drizzle.png
│       ├── humidity.png
│       ├── mist.png
│       ├── rain.png
│       ├── search.png
│       ├── snow.png
│       └── wind.png
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Harshit765G4/WeatherWeb_JavaScript_Project.git
cd WeatherWeb_JavaScript_Project
```

### 2. Open the project

Open:

```text
index.html
```

You can open it directly in your browser or use a local development server such as the **Live Server** extension in VS Code.

---

## 🖥️ Running with VS Code

A simple workflow is:

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

The application will open in your browser.

---

## 🎨 Styling

The interface is styled in `style.css`.

The current design includes:

- Dark page background
- Gradient weather card
- Rounded search input
- Circular search button
- Large temperature typography
- Weather illustration
- Two-column weather details section
- Responsive card width

---

## 🖼️ Weather Assets

The `weather-app-img/images` directory contains icons representing different weather conditions:

| Asset | Purpose |
|---|---|
| `clear.png` | Clear weather |
| `clouds.png` | Cloudy weather |
| `drizzle.png` | Drizzle |
| `rain.png` | Rain |
| `snow.png` | Snow |
| `mist.png` | Mist/fog |
| `humidity.png` | Humidity indicator |
| `wind.png` | Wind-speed indicator |
| `search.png` | Search button icon |

---

## 🔮 Planned JavaScript Functionality

The project name indicates a JavaScript-based weather application, and the current UI can be extended with JavaScript to make it fully dynamic.

Potential functionality includes:

- 🌍 Search weather by city
- ☁️ Fetch live weather data from a weather API
- 🌡️ Update temperature dynamically
- 💧 Display current humidity
- 💨 Display wind speed
- 🌤️ Change weather icons based on API response
- ❌ Show a message when a city is not found
- ⏳ Add loading states while fetching data
- 📍 Support current-location weather
- 📅 Add forecast information

A typical future flow would be:

```text
User enters city
       ↓
JavaScript reads input
       ↓
Weather API request
       ↓
API returns weather data
       ↓
JavaScript updates the DOM
       ↓
Weather card displays live information
```

---

## 🔌 Suggested API Integration

To make the application fully functional, a weather service such as **OpenWeatherMap**, **WeatherAPI**, or another weather provider can be integrated.

Example architecture:

```text
Frontend
   │
   │ City name
   ▼
JavaScript
   │
   │ API Request
   ▼
Weather API
   │
   │ JSON response
   ▼
JavaScript
   │
   ▼
Update HTML elements
```

> Never expose a private API key in a public repository. For production applications, use a secure backend or environment-based configuration where appropriate.

---

## 📌 Current Limitations

The current repository is primarily a UI implementation.

- Weather information is currently static.
- No JavaScript weather-fetching logic is included.
- No weather API is connected.
- Search input does not currently retrieve live city data.
- Weather icons are not dynamically selected based on conditions.

---

## 🔮 Future Improvements

- Add `script.js`
- Integrate a live weather API
- Add error handling for invalid cities
- Add loading indicators
- Detect the user's location
- Display feels-like temperature
- Display pressure and visibility
- Add sunrise and sunset information
- Add a multi-day forecast
- Improve accessibility
- Add temperature-unit switching between °C and °F
- Add dark/light themes
- Deploy the project using GitHub Pages, Netlify, or Vercel

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the project in a browser.
5. Open a pull request.

---

## 📄 License

This repository currently does not contain a dedicated `LICENSE` file.

Add an appropriate license if you plan to distribute or reuse the project publicly.

---

## 👨‍💻 Author

**Harshit Garg**

GitHub: [@Harshit765G4](https://github.com/Harshit765G4)

Repository: [WeatherWeb_JavaScript_Project](https://github.com/Harshit765G4/WeatherWeb_JavaScript_Project)

---

⭐ If you find this project useful, consider giving it a star!
