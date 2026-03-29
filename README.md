# 🐦 Darjeeling Bird Observations

Exploring 8,280 bird sightings from iNaturalist using Python — with a seasonal heatmap calendar and an interactive map.

---

## Dataset description and source

CSV with 9 columns: species, scientific name, date, latitude/longitude, observer, quality grade, and iNaturalist URL.  
Source: [iNaturalist](https://www.inaturalist.org) — Darjeeling, West Bengal.

---

##  What I  Built

### 1. Bird Calendar
A heatmap of the top 30 species vs. 12 months. Darker = more sightings. Built with `matplotlib`.

### 2. Observation Map
All sightings plotted as dots, colour-coded by season. Click any dot to see species, date, observer, and a link to iNaturalist. Built with `folium`.

| Season  | Months    | Colour |
|---------|-----------|--------|
| ❄️ Winter  | Dec–Feb   | Blue   |
| 🌿 Spring  | Mar–May   | Green  |
| 🌧️ Monsoon | Jun–Aug   | Purple |
| 🍂 Autumn  | Sep–Nov   | Orange |

---

## 🗺️ Map Preview

<img width="958" height="538" alt="image" src="https://github.com/user-attachments/assets/024c649c-8741-4447-8620-70faa26b4ee0" />

<img width="953" height="535" alt="image" src="https://github.com/user-attachments/assets/e63dc34e-181f-46a8-9ff6-3de9e73b5a97" />





---

## 🛠️ Libraries Used

- `pandas` — data loading and cleaning
- `matplotlib` — bird calendar heatmap
- `folium` — interactive map

---

---

*8,280 observations · Darjeeling, West Bengal · Data: iNaturalist*
