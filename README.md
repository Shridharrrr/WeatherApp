Here’s your cleaned-up and more concise **Weather Dashboard - Project Documentation**, with **Table of Contents**, **Deployment**, **Troubleshooting**, and **Contributing** sections removed:

---

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
git clone https://github.com/yourusername/weather-dashboard.git
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

| Variable                     | Description                            | Required |
| ---------------------------- | -------------------------------------- | -------- |
| `VITE_OPENWEATHER_API_KEY`   | OpenWeather API Key                    | ✅        |
| `VITE_BASE_URL` *(optional)* | API base URL (default used if not set) | ❌        |

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

---

## 🌐 API

**Endpoint:**
`GET https://api.openweathermap.org/data/2.5/weather`

**Parameters:**

| Name    | Description            | Example    |
| ------- | ---------------------- | ---------- |
| `q`     | City name              | `London`   |
| `appid` | Your API key           | `your_key` |
| `units` | `metric` or `imperial` | `metric`   |

Official Docs: [OpenWeatherMap - Current Weather](https://openweathermap.org/current)

---

Let me know if you'd like a downloadable `README.md` version or if you want to include screenshots, credits, or license info.
