# 🌦️ Weather Forecasting Analysis Dashboard  

## 📁 Project Overview  
This **Power BI dashboard** delivers a comprehensive analysis of **weather, air quality, and atmospheric conditions** for multiple Indian cities: **Ajmer, Kochi, Hyderabad, Bangalore, Mumbai, and Chennai**.  

It provides **real-time metrics** along with **7-day forecasts**, using clear visualizations and a user-centric design to make complex weather data easily interpretable.  

---

## 📊 Dashboard Features  

### 🌡️ Current Weather Overview  
- Displays current **temperature (30.9°C)** and weather condition for **Ajmer** (default city).  
- Users can toggle between cities for instant updates.  

### 📅 Forecasted Weather Trends  
- **Daily forecast cards** with temperature details.  
- **Trend line graph** for weekly variations in max/min temperatures.  

### 🌍 Detailed Atmospheric Data  
- **Visibility, humidity, pressure, wind speed, precipitation, UV index** represented in dedicated visuals.  
- **Sunrise & Sunset timings** (e.g., 05:55 AM & 07:18 PM) with intuitive icons.  
- **Rain probability (bar chart)** showing precipitation risk for each day.  

### 🌫️ Air Quality Index (AQI)  
- **Centralized gauge visual** (AQI = 122 → *Unhealthy for Sensitive Groups*).  
- Pollutant-level breakdown: **O₃, PM10, PM2.5, SO₂, CO, NO₂**.  
- **Color coding & advisory text** highlight public health risks.  

---

## 🛠 Data Preparation & Modeling  

### ⚡ Power Query  
- Imported & consolidated multi-city weather datasets.  
- Transformed data types, handled nulls, and standardized units (Celsius, kph).  
- Normalized text, removed duplicates, and filtered time-series records.  
- Optimized query steps for efficient analysis.  

### 📐 DAX (Data Analysis Expressions)  
- Built **custom measures & calculated columns** for:  
  - Daily average temperature  
  - AQI band classification  
  - Rain probability calculations  
- Applied **time intelligence** for rolling averages & week-over-week trends.  
- Created **slicers & city filter logic** for dynamic dashboard interactivity.  

### ✅ Additional Practices  
- Error handling for incomplete/inconsistent data.  
- Unified API & dataset integration across multiple sources.  

---

## 🎨 Visualization Techniques  
- **Card visuals** → For key metrics (temperature, AQI, etc.)  
- **Line graphs** → Forecasted weather trends  
- **Bar charts** → Rainfall probabilities  
- **Gauge charts** → AQI tracking  
- **Conditional formatting** → Highlights for AQI and precipitation risks  
- **Iconography** → Sun, rain, wind visuals for user-friendly design  

---

## 🚀 Key Benefits  
This dashboard empowers:  
- **Everyday users** → Plan daily activities with weather & air quality updates.  
- **Decision-makers** → Monitor environmental health trends across cities.  
- **Analysts** → Compare multi-city weather, AQI, and forecast data in one platform.  

---

---

## 📌 Future Enhancements  
- Add **historical weather trends** for long-term climate insights.  
- Incorporate **real-time live API connections** for automatic updates.  
- Extend coverage to **all major Indian cities** with drill-down options.  

---

preview : ![Dashboard Preview](https://github.com/sadik4li/Weather-Forecasting-Analysis/blob/main/Screenshot%202025-07-31%20100724.png)
