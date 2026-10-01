# 🌤️ React-Weather App

A simple and responsive **Weather Application built with React.js** that allows users to search for a city and view its current weather information.

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Display current temperature
* 💧 Show humidity information
* 💨 Display wind speed
* ☁️ Show weather conditions
* 📱 Responsive design for desktop and mobile
* ⚡ Fast and user-friendly interface
* 🔄 Fetches real-time weather data using a Weather API

## 🛠️ Technologies Used

* **React.js**
* **JavaScript (ES6+)**
* **HTML5**
* **CSS3**
* **Weather API**
* **Axios / Fetch API**
* **Vite / Create React App**

## 📂 Project Structure

```text
React-Weather-app/
│
├── public/
│
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── main.jsx
│   └── App.css
│
├── .gitignore
├── package.json
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/anmolagrahari24/React-Weather-app.git
```

### 2. Navigate to the project

```bash
cd React-Weather-app
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The application will run locally at the URL shown in your terminal, usually:

```text
http://localhost:5173
```

## 🔑 API Configuration

If your application uses an API key, create a `.env` file in the project root:

```env
VITE_WEATHER_API_KEY=your_api_key_here
```

Then access it in your React application using:

```javascript
import.meta.env.VITE_WEATHER_API_KEY
```

> Never upload your API key or `.env` file to GitHub.

## 💡 How It Works

1. User enters a city name in the search box.
2. The application sends a request to the weather API.
3. The API returns the current weather information.
4. React updates the UI with the weather details.
5. Users can search for another city whenever they want.


## 🎯 Future Improvements

* 📍 Detect weather using the user's current location
* 🌦️ Add a 5-day weather forecast
* 🌙 Add dark/light mode
* 🌡️ Add Celsius/Fahrenheit conversion
* 🌅 Add weather-based backgrounds
* 📊 Display additional weather information

## 👨‍💻 Author

**Anmol Agrahari**

* GitHub: `@anmolagrahari24`
* LinkedIn: `anmol-agrahari-8542132a2`

