<div align="center">

<img src="Logo/FUEL%20TRACKER%20WIDE.png" alt="FuelTrack" width="520" />

# ⛽ FuelTrack

**India-focused route, fuel, toll, vehicle, and trip-cost intelligence in one browser app.**

![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![Leaflet](https://img.shields.io/badge/Leaflet-Maps-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-Analytics-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![India](https://img.shields.io/badge/Focus-India-FF9933?style=for-the-badge)

<a href="https://github.com/sponsors/anshdeepofficial1"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Sponsor on GitHub" /></a>
<a href="https://buymeacoffee.com/anshdeepofficial1"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=000" alt="Buy Me a Coffee" /></a>

</div>

---

## ✨ Overview

FuelTrack is a single-page web application for estimating and understanding trip expenses across Indian routes. It combines route distance, vehicle mileage, fuel rates, toll logic, trip history, fuel logs, charts, and an in-app AI assistant in one interface.

## 🚀 Highlights

- Step-by-step route planner
- Map-based route visualization
- Distance and duration estimation
- Petrol, diesel, CNG, and EV-aware calculations
- Vehicle mileage and toll multipliers
- Fuel and toll cost breakdown
- Fuel purchase logs
- Trip history and dashboard summaries
- Analytics charts and monthly trends
- AI assistant for route/fuel/toll questions
- Fallback routing and estimation logic

## 🧠 Calculation Flow

**Total Trip Cost = Fuel Cost + Toll Cost**

Routing uses a layered fallback approach, while toll calculations prefer configured API data or known routes before falling back to estimation.

## 🔌 Integrations

- Mappls Routing API
- OSRM routing fallback
- OpenStreetMap Nominatim
- TollGuru API support
- Google Gemini API
- Leaflet
- Chart.js
- ArcGIS map tiles

## 🛠️ Tech Stack

| Area | Technology |
| --- | --- |
| Frontend | HTML, CSS, Vanilla JavaScript |
| Maps | Leaflet + ArcGIS tiles |
| Charts | Chart.js |
| Routing | Mappls + OSRM fallback |
| AI | Gemini integration |
| Architecture | Single-page, no-build web app |

## ⚡ Getting Started

```bash
git clone https://github.com/anshdeepofficial1/FuelTracker.git
cd FuelTracker
```

Open `index.html` directly in a browser or serve the folder with any static development server.

## 🔐 Configuration

Optional integrations depend on configuration values such as routing, toll, and AI API keys. For a public production deployment, sensitive credentials should be moved out of client-side code and protected behind server-side endpoints.

## ⚠️ Accuracy Note

Route distance, tolls, traffic, mileage, and fuel prices can change. Values produced by the app should be treated as planning estimates unless backed by a confirmed live source.

## 🤝 Contributing

Contributions are welcome, especially for broader toll coverage, persistent storage, modular architecture, testing, and stronger route intelligence.

---

<div align="center">
Built by <a href="https://github.com/anshdeepofficial1">Anshdeep Singh</a>
</div>
