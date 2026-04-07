# 🌦️ Weather App

> Search any city and get real-time weather instantly — built with React.js and designed to handle real-world user errors gracefully.

![React](https://img.shields.io/badge/React-JS-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?style=flat&logo=vite&logoColor=white)
![API](https://img.shields.io/badge/API-OpenWeatherMap-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat)

---

## 🚀 Live Demo

👉 [your-vercel-link.vercel.app](https://your-vercel-link.vercel.app)

---

## ✨ Features

- 🔍 **City search** — look up current weather anywhere in the world
- 🌡️ **Real-time data** — live conditions via the OpenWeatherMap API
- ⚡ **Fast & responsive** — snappy UI built with Vite + React
- ❗ **Smart error handling** — graceful feedback for every edge case

---

## ❗ Error Handling

| Scenario           | Behavior                                       |
| ------------------ | ---------------------------------------------- |
| 🚫 Empty input     | Prompts user to enter a city name              |
| 🔑 Invalid API key | Shows a clear authentication error             |
| 🌍 City not found  | Informs user the city doesn't exist in the API |

---

## 🧠 What I Learned

- React components and JSX fundamentals
- State management with `useState`
- Conditional rendering patterns
- Integrating third-party REST APIs
- Handling real-world edge cases and user errors

---

## 🛠️ Tech Stack

| Technology         | Purpose                 |
| ------------------ | ----------------------- |
| React.js           | UI framework            |
| JavaScript (ES6+)  | Core logic              |
| CSS                | Styling                 |
| Vite               | Build tool & dev server |
| OpenWeatherMap API | Weather data source     |

---

## ⚙️ Run Locally

**1. Clone the repository**

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

**2. Install dependencies**

```bash
npm install
```

**3. Set up your API key**

Create a `.env` file in the root of the project:

```env
VITE_API_KEY=your_api_key_here
```

> Get a free API key at [openweathermap.org](https://openweathermap.org/api)

**4. Start the development server**

```bash
npm run dev
```

The app will be running at `http://localhost:5173`

---

## 📁 Project Structure

```
weather-app/
├── public/
├── src/
│   ├── components/
│   ├── App.jsx
│   └── main.jsx
├── .env
├── index.html
└── package.json
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
