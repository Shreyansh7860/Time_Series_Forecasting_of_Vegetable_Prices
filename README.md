# 🧅 Time Series Forecasting of Vegetable Prices

This project forecasts future prices of vegetables (e.g., Onion, Potato, Tomato) using historical market data. The model uses Facebook Prophet, a powerful time series forecasting tool, to predict prices and visualize trends for the next 30 days.

---

## 📌 Project Overview

In agriculture-based economies like India, vegetable price fluctuation impacts farmers, retailers, and consumers. This project helps predict vegetable prices over time to aid in:

- **Market planning** for farmers and sellers  
- **Budget forecasting** for consumers  
- **Policy planning** for governments and NGOs

---

## 📊 Features

- Clean and preprocess real-world vegetable price data  
- Forecast prices for **multiple vegetables automatically**  
- Visualize historical trends and future forecasts  
- Use **Facebook Prophet** for time-series prediction  
- Generate separate plots for each vegetable

---

## 🛠️ Tech Stack

| Tool/Library   | Purpose                        |
|----------------|-------------------------------|
| Python         | Programming language           |
| Pandas         | Data cleaning and manipulation |
| Prophet        | Time-series forecasting        |
| Matplotlib     | Data visualization             |

---

## 📁 Dataset

The dataset should contain the following columns:
- `Commodity_Name` – Name of the vegetable
- `Centre_Name` – Market or city 
- `Price` – Daily or weekly vegetable price (Rs/kg)
- `date` – Date of the price record
