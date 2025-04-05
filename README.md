# International Space Station Tracker

![ISS Tracker Screenshot](screenshot.png)

A static website that displays the current position of the International Space Station with a spacecraft icon, crew information, and light/dark mode toggle.

## Features

- 🛰️ Real-time ISS position snapshot (at time of generation)
- 👨‍🚀 Current crew member information
- 🌍 Interactive map with custom spacecraft icon
- 🌗 Light/Dark mode toggle (changes water color to dark grey)
- 📱 Responsive design works on all devices
- ⏳ Static HTML (perfect for GitHub Pages)

## How It Works

This project uses:
- The [Open Notify API](http://open-notify.org/Open-Notify-API/) for ISS data
- [Leaflet.js](https://leafletjs.com/) for interactive maps
- Pure HTML/CSS/JavaScript (no frameworks needed)

The website shows:
- Current ISS latitude/longitude
- Number of astronauts aboard
- Crew member names
- Last update time
- Visual orbit path

## How to Use

1. Visit the [live GitHub Pages site](https://yourusername.github.io/repository)
2. View the ISS current position
3. Toggle dark mode using the button below the info panel

## Development

To regenerate the static HTML with current data:
```bash
python generate_iss_tracker.py
