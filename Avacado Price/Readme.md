# 🥑 Forecasting Avocado Prices 🥑📈

This notebook forecasts **avocado prices** in the U.S. using time series analysis with the `Prophet` library. We explore trends across different regions and years, with a focus on visualization and model interpretation.

---

## 🌟 What’s Inside?

- 🧼 Data cleaning and sorting
- 📊 Regional and yearly demand analysis
- 🔮 Prophet-based forecasting of average avocado prices
- 📆 Forecasting by region (e.g., **West**)
- 📉 Trend and seasonality visualization

---

## 🧰 Tech Stack

- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – visualization
- `Prophet` – forecasting

---

## 📁 Dataset

- 📄 `avocado.csv` from Project 4
- Columns used: `Date`, `AveragePrice`, `region`, `year`

---

## 📈 Workflow Steps

1. 🔍 Load and clean dataset
2. 🧠 Group and analyze by region/year
3. 🕒 Plot historical price trends
4. 🔮 Forecast avocado prices using Prophet
5. 🗺️ Focus on specific regions (e.g., West)
6. 📊 Plot seasonal and trend components

---

## 💡 Key Observations

- 🟢 Prices spike around **September**
- 🔺 Highest prices seen in **2017**
- 🔻 Lower prices observed in **2019**
- 📍 Regional variation plays a big role

---

## ▶️ Getting Started

```bash
pip install prophet pandas matplotlib seaborn
