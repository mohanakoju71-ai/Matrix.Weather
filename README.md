# 🌌 Matrix.Weather: Cyberpunk Meteorological Ingestion Terminal

A high-performance, responsive single-page web dashboard that handles real-time global weather telemetry. This system utilizes advanced asynchronous JavaScript and a multi-layered parsing grid to translate raw meteorological satellite data into an ultra-sleek, interactive dark-themed dashboard.

## 🚀 Key Architectural Features

* **Zero-Token REST API Integration:** Communicates with the open-source Open-Meteo platform via a two-stage asynchronous pipeline (Geocoding API coordinates lookup followed by core forecast array fetches).
* **Double-Tier Matrix Resolution:** Eliminates formatting and logic errors by cross-referencing World Meteorological Organization (WMO) codes alongside hard temperature range boundaries simultaneously.
* **Interactive Expandable Deck:** Uses fluid CSS max-height transitions (`cubic-bezier`) to keep detailed metrics (Humidity and Wind Speed) hidden under a minimal layout until a user expands it by clicking the central emoji element.
* **Cyberpunk Minimalist Dark Theme:** Features high-contrast neon accents, robust sans-serif typographic hierarchies, custom-crafted vector icons, and soft rounded radii applied uniformly across all layout cells.
* **Granular Promise Exception Chains:** Implements robust `try/catch` validation frameworks to catch unmapped cities or network timeout responses and immediately render human-readable system exception logs.

## 📁 Repository Blueprint

```text
weather-dashboard/
└── index.html       # Unified Semantic Layout, Cyberpunk Stiling, and Async API Script
