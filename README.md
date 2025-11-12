# ☀️ Solar Mapping India - Real-time Solar Energy Platform

> Real-time Solar Mapping Platform for India - Weather data, solar irradiance analysis, and energy predictions.

This is the frontend for the Solar Mapping India project, built with React, Vite, TypeScript, and Leaflet for interactive mapping.

## ✨ Features

* **Interactive Map:** Displays solar irradiance data on an interactive Leaflet map.
* **Real-time Data:** Connects to a backend API for live weather and solar predictions.
* **Component-Based:** Built with modern React and TypeScript.
* **Styled with Tailwind:** Utilizes Tailwind CSS for rapid, utility-first styling.

## 🛠️ Tech Stack

* **Framework:** [React](https://reactjs.org/)
* **Bundler:** [Vite](https://vitejs.dev/)
* **Language:** [TypeScript](https://www.typescriptlang.org/)
* **Mapping:** [Leaflet](https://leafletjs.com/) & [React-Leaflet](https://react-leaflet.js.org/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Routing:** [React Router DOM](https://reactrouter.com/)
* **Data Fetching:** [Axios](https://axios-http.com/)

---

## 🚀 Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (v18 or later recommended)
* A package manager (npm, yarn, or pnpm)

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/solar-mapping-frontend.git](https://github.com/YOUR_USERNAME/solar-mapping-frontend.git)
    cd solar-mapping-frontend
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Backend API:**
    This project requires a running backend. The `vite.config.ts` is pre-configured to proxy requests from `/api` to `http://localhost:5000`.

    Make sure your backend server is running on port 5000.

### Available Scripts

To run the app in development mode (with hot-reloading):
```bash
npm run dev
