# Weather Information Application

**Student ID:** 20901241  
**Repository:** weather-api-application  

---

## 1. Project Description
This project is a Python-based weather information application built in Google Colab. It interacts with the Open-Meteo REST API to retrieve current weather metrics (temperature, relative humidity, and wind speed) based on geographic coordinates provided by the user. It also utilizes reverse geocoding to display human-readable location names alongside weather data.

---

## 2. Technologies Used
- **Language:** Python 3
- **Environment:** Google Colab
- **Libraries:** `requests`, `geopy`
- **Data Format:** JSON
- **Version Control:** Git & GitHub

---

## 3. API Used
- **Open-Meteo REST API:** `https://api.open-meteo.com/v1/forecast`
- **Geopy (Nominatim):** Reverse geocoding service

---

## 4. How to Run
1. Open `Weather_API_Application_20901241.ipynb` in Google Colab.
2. Run the package installation cell (`!pip install requests geopy`).
3. Run all setup cells sequentially to load functions and libraries.
4. Execute `run_application()` in the testing cell.
5. Enter latitude (e.g., `23.5880`) and longitude (e.g., `58.3829`) when prompted.

---

## 5. Example Output

```text
================================
      WEATHER INFORMATION       
================================
Location    : Muscat, Oman
Coordinates : 23.5880, 58.3829
--------------------------------
Temperature : 31 °C
Humidity    : 62 %
Wind Speed  : 4.5 km/h
================================
