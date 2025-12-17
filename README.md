# 🌍 WorldWise

WorldWise is a travel tracking application that allows users to bookmark cities they have visited across the globe. The app features an interactive map, city/country listings, and a personal diary of travel experiences.

## 🚀 Features

- **Interactive Map**: Click anywhere on the map to add a new city to your list.
- **Location Tracking**: Automatically fetch your current location via geolocation.
- **City & Country Management**: View your travels organized by specific cities or grouped by countries.
- **Dynamic Routing**: Uses nested routes to manage different views within the app dashboard.
- **Global State**: Managed entirely through the Context API for a seamless user experience.

---

## 🛠️ Tech Stack

- **Framework**: [React](https://reactjs.org/)
- **Routing**: [React Router](https://reactrouter.com/) (Nested routes, Protected routes, URL Search Params)
- **State Management**: **Context API** (Used for global city data and authentication state)
- **Data Fetching**: **useEffect** (Standard side-effect management for API calls)
- **Styling**: CSS Modules
- **Map Integration**: [React Leaflet](https://react-leaflet.js.org/)
- **Backend**: JSON Server (Mock API)

---

## 📁 Project Structure

```text
src/
├── components/     # Reusable UI components (Sidebar, Map, CityItem, etc.)
├── contexts/       # Context providers (CitiesContext, AuthContext)
├── hooks/          # Custom hooks (useGeolocation, useUrlPosition)
├── pages/          # Main route components (Homepage, AppLayout, Login)
└── App.jsx         # Main application component with Route definitions
```

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/lexopez/worldwise_reactjs.git
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run the development server

```bash
npm run dev
```

### 3️⃣ Run the json server

```bash
npm run server
```

---
