# Weather_Rain_Prediction

# 🌧️ Rain Prediction Using OpenWeatherMap API

This project uses the **OpenWeatherMap API** to fetch real-time weather data and predicts whether it will **rain today or not** based on the response data.

---

## 🔍 Project Objective

- Fetch current weather conditions for any city using an API.
- Analyze weather parameters like:
  - Cloud cover
  - Humidity
  - Rain volume (if present)
- Predict whether it will rain today (`Yes` or `No`) using rule-based logic or integrate with a trained ML model.

---

## 🔧 Tech Stack

- Python
- Requests (API call)
- OpenWeatherMap API
- (Optional) Flask – to create an API/web app
- (Optional) Machine Learning model (trained on historical weather data)

---

## 🔑 API Setup

1. Get a free API key from OpenWeatherMap:  
   🔗 https://openweathermap.org/api

2. Replace this line in your script:

```python
API_KEY = 'your_actual_api_key'
