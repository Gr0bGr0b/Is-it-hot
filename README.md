# Is It Hot? 🌡️

A simple weather application built with **Astro** to check the current temperature at your location and determine if it's hot or not.

## 💡 Project Idea

This project demonstrates a fun, minimalist approach to building web applications with Astro. It fetches your location using IP geolocation and retrieves real-time weather data, displaying the current temperature with a humorous message about whether it's hot outside.

## 🛠️ Tech Stack

- **[Astro](https://astro.build)** (v6.3.7) - Modern static site builder with zero-JS by default
- **Environment Variables** - For secure API key management

## 🌍 API Integration

The app uses:
- **IPinfo API** - Determines your location from your IP address
- **OpenWeatherMap API** - Fetches real-time weather data based on coordinates

## 🚀 Quick Start

### Prerequisites
- Node.js >= 22.12.0
- Yarn or npm

### Setup

1. Clone the repository:
```bash
git clone <repo-url>
cd is-it-hot
```

2. Install dependencies:
```bash
yarn install
```

3. Create a `.env` file with your API keys:
```env
SECRET_IP_TOKEN=your_ipinfo_token
SECRET_WEATHER_API=your_openweathermap_api_key
```

4. Start the development server:
```bash
yarn dev
```

The app will be available at `http://localhost:4321`

## 📋 Available Commands

| Command | Action |
|---------|--------|
| `yarn dev` | Start local dev server at `localhost:4321` |
| `yarn build` | Build production site to `./dist/` |
| `yarn preview` | Preview production build locally |
| `yarn astro ...` | Run Astro CLI commands |

## 📁 Project Structure

```
/
├── public/           # Static assets
├── src/
│   └── pages/
│       └── index.astro    # Main weather display page
└── package.json
```

## 🎯 Features

- ✨ Displays current temperature at your location
- 🎭 Humorous messages based on temperature
- 🌐 Automatic location detection
- 📱 Responsive design
- ⚡ Fast, static-first rendering with Astro

## 📚 Learn More

- [Astro Documentation](https://docs.astro.build)
- [Astro Discord Community](https://astro.build/chat)
- [OpenWeatherMap API](https://openweathermap.org/api)
- [IPinfo API](https://ipinfo.io)
