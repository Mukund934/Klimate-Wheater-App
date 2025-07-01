
---

# 🌤️ Klimate – A Beautiful Weather Forecast App

📍 Real-time weather updates, powered by **TanStack Query**, **React**, **TypeScript**, and the elegance of **ShadCN UI**.

---

## 📖 Overview

**Klimate** is a sleek and responsive weather web app that fetches and displays weather data in real-time based on city search and geolocation. It provides a user-friendly UI with modern tooling like **Tailwind CSS**, **TanStack Query**, and **Recharts** for data visualizations — built with scalability and performance in mind.

Through this project, I deepened my understanding of component-based architecture, dynamic routing, API integration, query caching, and custom hooks in React using TypeScript.

---

## 🌟 Features

### 🔍 City Search & Autocomplete

Search any city in the world and instantly get weather data via OpenWeather API.

### 📍 Geolocation Support

Automatically detect your current location to show localized weather updates.

### 📊 Hourly Forecasts

Visualized hourly temperature graphs using **Recharts** with clean and responsive charts.

### 💾 Favorites & Local Storage

Mark favorite cities and save them locally using `localStorage` — persists between reloads.

### 🌓 Dark / Light Theme Toggle

Seamless theme switching using **ThemeProvider** from ShadCN and context API.

### 🧭 Custom Hooks

Encapsulated weather logic, favorites, geolocation, and localStorage into reusable **custom hooks**.

---

## 🚀 Live Project

🔗 [Visit Klimate →]()

---

## 🛠️ Tech Stack

### ⚛️ Frontend

* **React 18 + TypeScript**
* **Vite** for lightning-fast dev build
* **Tailwind CSS** for responsive styling
* **ShadCN UI** for elegant component library
* **Recharts** for plotting hourly temperatures
* **TanStack Query (React Query)** for API calls, caching, and loading states

### 🧠 Architecture & Concepts Learned

| Concept            | Description                                                                |
| ------------------ | -------------------------------------------------------------------------- |
| `ThemeProvider`    | For global dark/light mode using context API                               |
| `Layout Component` | Reusable layout structure with header, body, and footer                    |
| `React Router DOM` | For client-side routing between dashboard and city-specific views          |
| `Query Client`     | Provides the core for all TanStack queries and caching logic               |
| `Query Keys`       | Unique identifiers for caching each city’s weather data                    |
| `Stale Time`       | Used to control freshness of weather API response before refetching        |
| `Devtools`         | Real-time debugging with React Query DevTools                              |
| `Custom Hooks`     | Reusable logic for favorites, weather API, search history, and geolocation |

---

## 🧪 API Integration

* **OpenWeatherMap API**
  Used to fetch current and hourly weather data via:

  * `https://api.openweathermap.org/data/2.5/weather`
  * `https://api.openweathermap.org/data/2.5/forecast`

* **Geocoding API**
  To convert between city name and coordinates.

---

## 📁 Project Structure

```
tanstack-query-weather-app/
├── public/
│   ├── logo.png           ← Custom app icon
│   └── vite.svg
├── src/
│   ├── api/               ← API configs and types
│   ├── components/        ← UI + functional components
│   ├── context/           ← Theme provider setup
│   ├── hooks/             ← Custom React hooks
│   ├── pages/             ← Main dashboard and city views
│   └── App.tsx            ← Root app component
├── index.html             ← Favicon + root div
├── vite.config.ts         ← Vite + TS config
├── tailwind.config.js     ← Tailwind theme setup
└── .env                   ← Your API key
```

---

## 🏗️ Local Setup

### ⚙️ Prerequisites

* Node.js ≥ 18
* npm or yarn
* OpenWeather API Key

### 🔧 Installation

```bash
git clone https://github.com/Mukund934/Klimate-Wheather-APP.git
cd Klimate-Wheather-APP
npm install
```

Create a `.env` file in root with:

```
VITE_OPENWEATHER_API_KEY=your_api_key_here
```

### ▶️ Start Dev Server

```bash
npm run dev
```

---

## 🧑‍💻 What I Learned

✅ TanStack Query for modern data-fetching
✅ Query Keys, caching strategies, staleTime
✅ Recharts integration for weather visuals
✅ ShadCN UI for production-ready components
✅ Context API with ThemeProvider
✅ Creating clean reusable custom hooks
✅ Responsive Tailwind layouts
✅ Routing with React Router v6

---

## 📦 Deployment

Deployed on **Vercel** with auto builds from `main` branch.
Every push = instant live update.

---

## 🎯 Future Improvements

* 🌐 Add multi-language support
* 🧭 Add map-based city search (using Leaflet)
* 🗣️ Voice search for weather queries
* 📱 PWA support for mobile install
* 🔔 Push notifications for weather alerts

---

## 🤝 Contributing

Want to improve or extend Klimate? PRs are welcome!
**Fork → Code → Commit → Pull Request 🚀**

---

## 📜 License

Licensed under the **MIT License**.
View the [LICENSE](./LICENSE) for more details.

---

## 📬 Contact

👨‍💻 Built with love by [Mukund Thakur](https://github.com/Mukund934)
📩 Email: `mukund.th04@gmail.com`
🔗 GitHub: [Mukund934](https://github.com/Mukund934)

---

Let me know if you'd like me to:

* Add project shields (Live →, Version, License)
* Polish it for deployment badges
* Add preview GIFs/screenshots

Would you like this written directly into a `README.md` file now?
