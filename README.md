# 🌅 AMS2 Solar Session Planner

A lightweight web application built for **Automobilista 2** sim racers. It allows users to quickly calculate real-world solar positions for any track on any date to find the ideal hourly in-game session start time for sunrise and sunset stints.

![Automobilista 2 Sunset Racing](https://img.shields.io/badge/Sim%20Racing-Automobilista%202-amber)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

## 🚀 Features

* **Hourly Match Engine:** Converts precise solar timestamps into whole hourly recommendations matching AMS2's session setup options.
* **Track Location Database:** Pre-configured coordinates for popular AMS2 circuits across Europe, North America, South America, Asia, and Oceania.
* **Interactive Dark Map:** Leverages OpenStreetMap and Leaflet.js to pinpoint circuit locations visually.
* **Local Track Timezones:** Displays sunrise, sunset, and twilight phases adjusted to the real-world timezone of each circuit.
* **Zero Backend Costs:** Runs entirely client-side using native JavaScript and open-source astronomical calculations (`SunCalc`).

---

## 🛠️ Built With

* **HTML5 & Vanilla JavaScript**
* **Tailwind CSS** (via CDN for responsive layout)
* **[SunCalc.js](https://github.com/mourner/suncalc)** (Solar position calculation library)
* **[Leaflet.js](https://leafletjs.com/)** + **[OpenStreetMap](https://www.openstreetmap.org/)** (Interactive mapping)

---

## ⚡ Quick Start

### 1. Local Setup
No build tools or package managers required. Simply clone the repository or download the files:

```bash
git clone [https://github.com/YOUR-USERNAME/ams2-solar-finder.git](https://github.com/YOUR-USERNAME/ams2-solar-finder.git)
cd ams2-solar-finder
