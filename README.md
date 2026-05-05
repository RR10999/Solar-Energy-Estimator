# ☀️ Solar Energy Estimator

A smart, data-driven web application that estimates solar energy generation, savings, and system performance based on real-world Indian climate and environmental data.

---

## 🚀 Overview

The **Solar Energy Estimator** helps users evaluate the feasibility of installing rooftop solar panels by providing:

* ⚡ Daily & annual energy generation
* 💰 Estimated yearly savings
* 📉 Payback period (with subsidy consideration)
* 🌍 Environmental impact (CO₂ reduction, trees equivalent)
* 📊 Detailed performance breakdown and loss analysis

The app integrates realistic parameters such as **temperature, cloud cover, AQI, rainfall, and system losses** to produce accurate estimates.

---

## 🧠 Key Features

### 🔍 Smart City Selection

* Autocomplete search for **50+ Indian cities**
* Auto-loads:

  * Peak Sun Hours (PSH)
  * Temperature
  * Wind speed
  * AQI
  * Cloud cover
  * Electricity tariff

### ⚙️ System Configuration

Users can customize:

* Roof area
* Panel type (Poly, Mono PERC, TOPCon, HJT)
* Inverter type
* Tilt angle
* Usable roof percentage

---

### 📈 Advanced Calculations

Includes real-world factors:

* Temperature derating (NOCT model)
* Cloud attenuation
* Air pollution (AQI impact)
* Dust/soiling losses
* Tilt deviation loss
* Inverter + wiring losses

---

### 📊 Detailed Output

* Monthly generation chart
* Loss stack (IEC 61724 / NREL PVWatts model)
* Financial analysis (ROI, payback)
* Environmental impact metrics

---

## 🧪 Technologies Used

* **HTML5**
* **CSS3 (Custom styling, responsive UI)**
* **Vanilla JavaScript**
* No external frameworks (fully lightweight)

---

## 📂 Project Structure

```
Solar-Energy-Estimator/
│
├── index.html   # Main application file
```

---

## 🌐 Deployment

This is a static web app and can be deployed easily using:

* GitHub Pages
* Netlify
* Vercel

### ▶️ Run Locally

Simply open:

```
index.html
```

in your browser.

---

## 📊 Data Sources

* ☀️ MNRE Solar Resource Atlas / PVGIS
* 🌦️ IMD (Indian Meteorological Department)
* 🌫️ CPCB (Air Quality Index data)
* ☁️ ERA5 Climate Reanalysis
* ⚡ DISCOM Tariff Data (FY 2023–24)
* 📉 NREL PVWatts & IEC 61724 Loss Models

---

## 💡 Use Cases

* Homeowners evaluating solar installation
* Students learning renewable energy systems
* Quick feasibility analysis for rooftop solar
* Educational demonstrations

---

## 📌 Future Improvements

* Add real-time API-based weather data
* Mobile app version
* Cost breakdown by state
* Battery storage simulation
* Export results as PDF
