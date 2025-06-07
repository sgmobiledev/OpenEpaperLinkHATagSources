# 🖼️ OpenEpaperLink BLE Tag Display Scripts

**YAML scripts for Home Assistant displays on BLE E-Paper tags, designed for use with OpenEpaperLink.**

This repository includes preconfigured display layouts for various screen sizes and tag types (SoluM, Gicisky, Hanshow, Chroma), integrating popular Home Assistant sensors and services such as Ecowitt, OpenUV, Flightradar24, DWD, and more.

---

## 📁 Folder Structure

### 🧾 1.54" SoluM E-Paper Tags

Tested with SoluM 1.54" displays (152x152 px).

| File | Preview | Description |
|------|---------|-------------|
| `1.54-dreo-fan-mini.yaml` | ![](/images/dreo_fan_mini.jpg) | Displays Dreo Tower Fan status.<br>Requires [Dreo HA Integration](https://github.com/JeffSteinbok/hass-dreo) + `media/dreo.jpg`. |
| `1.54-aqara-tvoc-mini.yaml` | ![](/images/1.54-aqara-tvoc-air.jpg) | Air quality from Aqara TVOC Zigbee sensor. |
| `1.54-weather-wind-compass.yaml` | – | Weather from WundergroundPWS via Ecowitt. |
| `1.54-waste-collection-calender.yaml` | ![](/images/1.54-waste-collections-calender.png) | Waste collection schedule (requires region config via Müllkalender integration). |
| `1.54-openuvindex_mini.yaml` | ![](/images/1.54.openuvindex_mini.png) | UV index display via OpenUV. |
| `1.54-ecowitt-wh51-soil.yaml` | ![](/images/1.54.ecowitt_wh51_soil_mini.png) | Soil data from WH51 sensor via Ecowitt API. |
| `1.54-smart-air.yaml` | ![](/images/1.54-smart_air.png) | Air quality sensor display via SmartAir Zigbee. |
| `1.54-solar-rain-alert.yaml`<br>`1.54-solar-rain-alerter-V2.yaml` | ![](/images/1.54-solar_rain_mini.jpg) | Solar-powered Zigbee rain sensor alert. |
| `1.54-openplant-soil.yaml` | ![](/images/1.54-openplant-motion-soil.jpg)<br>![](/images/1.54-openplant-stand.jpg) | Soil/motion data with OpenPlant. Includes 3D printable stand (STL in `/stl`). |
| `1.54-flightradar.yaml` | ![](/images/1.54.flightradar.jpg) | Local air traffic from Flightradar24 (Nuremberg airport example). |
| `1.54-medi-marker.yaml` | ![](/images/1.54.medi-marker.jpg) | Displays Medication Marker. Must add homeassistant helper for my four medi. 
 `1.54-uv-stufe-dwd.yaml` | ![](/images/1.54-uv-stufe-dwd.jpg) | Displays UV index pyramid. Must add homeassistant HACS Integration [UV-INDEX-CARD](https://github.com/t1gr0u/uv-index-card). 
---

### 🧾 2.13" Gicisky E-Paper Tags

Resolution: 250x132 px

| File | Preview | Description |
|------|---------|-------------|
| `2.13.dwd-pollen-warning.yaml` | ![](/images/2.13.dwd-pollenflug.jpg) | Pollen alerts from DWD. |
| `2.13.openuv-warning.yaml` | ![](/images/2.13.openuv.jpg) | UV warnings via OpenUV. |
| `2.13-hochwasserportal-pegelstaende.yaml` | – | Flood levels from Hochwasserportal. |

---

### 🧾 2.2" SoluM E-Paper Tags

Resolution: 250x122 px

| File | Preview | Description |
|------|---------|-------------|
| `2.2-openplant-soil.yaml` | ![](/images/2.2.openplant-soil-soluM.jpg) | OpenPlant soil data. |
| `2.2-ecowitt_wh51_soil_4ch.yaml` | ![](/images/2.2.ecowitt_wh51_soil_4ch.jpg) | 4-channel WH51 soil display via Ecowitt. |
| `2.2-lunar-phase.yaml` | ![](/images/2.22.lunar-phase.jpg) | moon-stand on 2.2 over lunar phase integration [Integration source](https://github.com/ngocjohn/lunar-phase)|

---

### 🧾 2.66" SoluM E-Paper Tags

Resolution: 296x152 px

| File | Preview | Description |
|------|---------|-------------|
| `2.66-openuv.yaml` | ![](/images/2.66-openuv.jpg) | OpenUV Warning. |
| `2.66-sun-stand.yaml` | ![](/images/2.66-sun-stand.jpg) | Sun and Moon stand.Calculation based on https://github.com/ngocjohn/lunar-phase?tab=readme-ov-file#using-the-home-assistant-ui integration. |
| `2.66-ecowitt_wh51_soil_4ch.yaml` | ![](/images/2.66-ecowitt.wh51.jpg) | Ecowitt WH51 Soil Motion sensor. |
---


### 🧾 2.9" Gicisky E-Paper Tags

Resolution: 296x128 px

| File | Preview | Description |
|------|---------|-------------|
| `2.9-accu-weather.yaml` | ![](/images/2.19.accuweather.jpg) | Weather from AccuWeather. |
| `2.9-hochwasserportal-pegelstaende.yaml` | ![](/images/Wasserstand.svg) | Flood levels. |
| `2.9-waste-collection.yaml` | – | Waste schedule display via Müllkalender. |

---

### 🧾 3.5" Handshow E-Paper Tags

Resolution: 384x184 px

| File | Preview | Description |
|------|---------|-------------|
| `3.5-dwd-weather-warning.yaml` | – | DWD weather alerts. |
| `3.5-dwd-weather-lighting-warning.yaml` | ![](/images/3.5.dwd-weather-lightning-warn.jpg) | Lightning warning view. |

---

### 🧾 4.2" Handshow E-Paper Tags

Resolution: 400x300 px

| File | Description |
|------|-------------|
| `4.2-flight-radar.yaml` | Flightradar24 integration.<br>Requires modification for your airport and use case.<br>[Integration source](https://github.com/AlexandrErohin/home-assistant-flightradar24) |
| `4.2-dwd-weather.yaml` | DWD weather integration. Modify YAML for your use case. |

---

### 🧾 7.4" Chroma E-Paper Tags

Resolution: 640x384 px

| File | Preview | Description |
|------|---------|-------------|
| `7.4-dwd-weather-ranking-hh-n.yaml` | ![](/images/chroma75_dwd_ranking.png) | Compares weather rankings between Hamburg and Nuremberg. |

---

### 🧾 7.5" Hanshow E-Paper Tags

Resolution: 800x480 px

| File | Preview | Description |
|------|---------|-------------|
| `7.5-pws-weather.yaml` | ![](/images/7.5_hanshow_PWS.jpg) | Ecowitt PWS weather display (Nuremberg). |

---

## 🧰 Other Resources

### `ha-template-sensors.yaml`

- Template sensors to extend Home Assistant functionality.
- Includes CAPE and Lifted Index sensors.|
### `ha-helper`
- Add to your `\homeassistant-configs\input-helpers.yaml`.

### `medi-marker-card`
- Add to your `\homeassistant-configs\medi-marker-card.yaml`.

### `/media/`

- Fonts required for certain scripts (e.g., AccuWeather).
- Copy to:  
  `/homeassistant/custom_components/open_epaper_link/`

### `/images/`

- Display examples for each YAML script.

### `/stl/`

- 3D printable parts (e.g., OpenPlant stand).

---

## 📐 Supported Display Sizes

| Tag Size | Resolution |
|----------|------------|
| 1.54"    | 152x152    |
| 2.13"    | 250x132    |
| 2.2"     | 250x122    |
| 2.66"    | 296x152    |
| 2.9"     | 296x128    |
| 3.5"     | 384x184    |
| 4.2"     | 400x300    |
| 7.4"     | 640x384    |
| 7.5"     | 800x480    |

---

## 📦 Installation Notes

> To use fonts in scripts (e.g., for AccuWeather):
1. Place the font file in your `/media/` directory.
2. Copy the font to your Home Assistant folder:  
   `/homeassistant/custom_components/open_epaper_link/`

---

## ✅ Contributing

Pull requests are welcome! Please ensure that:
- YAML is valid and tested.
- Tags are correctly sized.
- External dependencies are noted clearly.

---

## 🧾 License

This repository is released under the MIT License.  
3D models may be subject to separate licenses (see `/stl` folder).

---
