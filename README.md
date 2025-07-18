
# Weather Dashboard - Project Documentation

## 📌 Overview

A responsive weather app built with **Vite**, **JavaScript**, and **Tailwind CSS**. It fetches real-time weather data from the OpenWeatherMap API.

---

## 🌟 Features

* Search weather by city
* Display temperature, condition, humidity & wind speed
* Weather icons
* Responsive design
* Error handling for invalid inputs

---

## ⚙️ Setup

### Prerequisites

* Node.js v16+
* npm or yarn
* OpenWeatherMap API key

### Installation

```bash
git clone https://github.com/Shridharrrr/WeatherApp.git
cd weather-dashboard
npm install
```

### Configuration

Create a `.env` file in the root directory:

```bash
touch .env
```

Add this to `.env`:

```
VITE_OPENWEATHER_API_KEY=your_api_key
```

---

## 🚀 Usage

### Development

```bash
npm run dev
```

### Production

```bash
npm run build
npm run preview
```

---

## 🔐 Environment Variables

| Variable                     | Description                            |
| ---------------------------- | -------------------------------------- | 
| `VITE_OPENWEATHER_API_KEY`   | OpenWeather API Key                    | 
| `VITE_BASE_URL` *(optional)* | API base URL (default used if not set) |

---

## 📁 Project Structure

```
├── public/           
├── src/
│   ├── assets/
│   ├── style.css     
│   └── main.js       
├── index.html
├── .env
├── tailwind.config.js
└── vite.config.js
```

Official Docs: [OpenWeatherMap - Current Weather](https://openweathermap.org/current)
