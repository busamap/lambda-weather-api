# 🌦️ Lambda Weather API (Serverless Project)

This project is a serverless weather API built with **AWS Lambda**, **API Gateway**, and **OpenWeatherMap API**. It fetches real-time weather data for a given city using Python and the `requests` library.

---

## 🔧 How It Works

- User hits the API Gateway endpoint with a `city` query (e.g., `?city=Lagos`)
- API Gateway triggers the Lambda function
- Lambda uses `requests` to fetch weather info from OpenWeatherMap
- Lambda returns temperature, city name, and weather description in JSON

---

## 🧪 Sample Response

```json
{
  "city": "Lagos",
  "temperature": 25.5,
  "description": "overcast clouds"
}
