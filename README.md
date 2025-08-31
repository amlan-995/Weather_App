🌦 Weather App

A simple and responsive Weather Application built using HTML, CSS, and JavaScript.
It fetches real-time weather data from the OpenWeatherMap API and displays it in a user-friendly interface.

✨ Features

🔍 Search weather by city name.

🌡 Displays temperature, humidity, and wind speed.

🌥 Shows corresponding weather icons (sunny, cloudy, rainy, etc.).

📱 Responsive design that works across devices.

⚡ Uses fetch API for real-time data fetching.

🛠️ Technologies Used

HTML5 → Structure of the app.

CSS3 → Styling and responsive layout.

JavaScript (ES6) → Fetching API data and DOM manipulation.

OpenWeatherMap API → Provides real-time weather details.

📸 Preview


<img width="220" height="242" alt="{CE703CCE-FB35-4EF7-A8EF-9EF3CCA6B805}" src="https://github.com/user-attachments/assets/4c895b70-3cdb-4d7c-8afe-81fd349be362" />


📂 File Structure
weather-app/
│── index.html      # Main HTML file
│── style.css       # Styling
│── script.js       # JavaScript logic
│── images/         # Weather icons

⚡ How it Works

User enters a city name in the search box.

JavaScript fetches weather data using the OpenWeatherMap API.

The app updates the DOM with live weather details and an icon.

🌍 Example API Request
fetch("https://api.openweathermap.org/data/2.5/weather?units=metric&q=London&appid=YOUR_API_KEY")
   .then(response => response.json())
   .then(data => console.log(data));
