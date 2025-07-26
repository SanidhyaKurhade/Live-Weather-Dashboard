# 🌍 Live Weather Dashboard (Power BI + OpenWeather API)

This project demonstrates a **real-time and interactive Power BI dashboard** that integrates with the **OpenWeather API** to display **current weather conditions**, **5-day forecasts**, and **air quality data** for multiple cities worldwide.

---

## 🔍 Objective
To provide a dynamic and automated weather monitoring dashboard that enables analysis of:

- **Current weather conditions** (temperature, humidity, pressure)
- **5-day forecast trends**
- **Air pollution metrics (AQI)**
- **Top cities ranked by highest and lowest temperatures globally**

---

## 📊 Key Features

### ✅ **Page 1: Global Weather Overview**
- KPIs for **current temperature, humidity, wind speed**
- Top **10, 20, and 30 cities** ranked by temperature
- Bar and map visuals for **temperature distribution by city**
- Weather condition breakdown (clear, cloudy, rainy)

### ✅ **Page 2: Forecast Analysis**
- **5-day forecast** with temperature and weather conditions
- Line charts for **min/max temperature trends**
- Dynamic city selection for forecast visualization

### ✅ **Page 3: Air Quality Insights**
- AQI levels by city (Good, Moderate, Unhealthy)
- Bar chart: **Pollution component distribution (CO, NO₂, O₃)**
- Correlation of **AQI with temperature and humidity**

---

## 🛠 Tools Used
- **Power BI Desktop** (Dashboard creation)
- **Power Query (M language)** (API integration)
- **OpenWeather API** (Current weather, forecast, air quality)
- **Power BI Service** (Scheduled refresh and sharing)

---

## 📈 Key Insights
- **City with highest temperature today:** Riyadh (48°C)
- **City with lowest temperature today:** Moscow (-10°C)
- **AQI Alert:** New Delhi & Beijing recorded **Unhealthy** levels
- **Forecast:** Tokyo expecting **rain for next 3 days**

---

## ⚡ How It Works
1. **OpenWeather API** provides real-time weather, forecast, and AQI data
2. **Power Query M scripts** call the API and transform JSON responses
3. **Power BI dashboard** visualizes data with dynamic ranking and filters
4. **Power BI Service** schedules daily refresh for automation

---
