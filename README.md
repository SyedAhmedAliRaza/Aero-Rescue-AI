# 🌍 Aero-Rescue AI Global

**AI-powered global respiratory safety and air-quality aware travel risk intelligence system**

Aero-Rescue AI is an advanced Streamlit-based intelligent health and environmental analytics platform that evaluates **air quality, pollen exposure, wildfire activity, and medical risk factors** to generate **real-time travel safety recommendations** for users worldwide.

It combines **live APIs + WHO datasets + regional pollution models + AI-driven risk scoring** to help users make safe travel and health decisions—especially for asthma, COPD, allergy, and respiratory-sensitive individuals.

---

## 🚀 Key Features

### 🌫️ Global Air Quality Intelligence
- Real-time & historical AQI estimation
- WHO-based regional pollution modeling
- 150+ global cities coverage across 6 continents

### 🏥 Medical Risk Assessment Engine
- Condition-aware risk scoring (Asthma, COPD, Heart Disease, etc.)
- Severity-based personalized health adjustment
- WHO PM2.5 standard-based calculations

### 🌸 Pollen Exposure Analysis
- Seasonal pollen tracking (high-risk months: March–May)
- Species-level pollen triggers (e.g., Paper Mulberry, Eucalyptus)
- Allergy & asthma impact estimation

### 🔥 Wildfire Monitoring (NASA FIRMS)
- Live satellite-based fire detection
- Regional hazard overlay system
- Confidence-based fire intensity filtering

### 🚑 Global Hospital & Emergency Network
- WHO-style hospital database integration
- ICU, oxygen, ventilator availability tagging
- Emergency contact auto-mapping by country

### ✈️ Travel Risk Intelligence Engine
- Origin vs destination risk comparison
- Smart travel recommendations:
  - ✅ Recommended routes
  - ⚠️ Caution alerts
  - ❌ High-risk travel warnings

### 🗺️ Interactive Global Map Dashboard
- Folium-based geospatial visualization
- Real-time environmental overlays
- City-level health risk indicators

---

## 🧠 AI Risk Scoring System

Aero-Rescue AI computes a **composite health risk score** using:

- PM2.5 concentration (real-time + seasonal blending)
- Medical condition multipliers
- Severity scale (1–5)
- Pollen exposure risk
- Travel mode & vehicle type adjustments

### Risk Formula Logic
- Base pollution risk (WHO standard 15 µg/m³)
- Condition multiplier (Asthma, COPD, etc.)
- Environmental modifiers (season + pollen)
- Travel exposure factor (flight, car, bus, AC/non-AC)

---

## 🏗️ System Architecture

Streamlit UI<br>
│<br>
├── Global City Database (150+ cities)
<br>
├── WHO Health Facilities Dataset
<br>
├── Pakistan EPA Air Quality Dataset
<br>
├── Pollen Exposure Dataset
<br>
├── NASA FIRMS Fire Data API
<br>
├── OpenWeatherMap AQI API
<br>
│
<br>
Risk Engine (AI Scoring Layer)
<br>
│
<br>
Travel Recommendation Engine
<br>
│
<br>
Interactive Map Visualization (Folium)

---

## 🧰 Tech Stack

- **Frontend/UI:** Streamlit
- **Mapping:** Folium + Streamlit-Folium
- **Data Processing:** Pandas, NumPy
- **Async Networking:** aiohttp, asyncio
- **APIs:**
  - OpenWeatherMap Air Pollution API
  - NASA FIRMS Wildfire API
- **Visualization:** Interactive Geo Maps
- **Backend Logic:** Python (scientific computing stack)

---

## 📌 Future Improvements
- AI chatbot for health recommendations
- Mobile app integration
- Predictive pollution forecasting (LSTM/Transformers)
- Real-time wearable device integration
- Satellite imagery-based pollution heatmaps
