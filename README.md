# 📊 5 Green / Red Candles Indicator

A simple and effective Pine Script indicator for TradingView that detects **5 consecutive bullish or bearish candles** and marks them directly on the chart.

---

## 🚀 Overview

This indicator identifies:

* ✅ **5 consecutive green (bullish) candles**
* 🔴 **5 consecutive red (bearish) candles**

It helps traders quickly spot short-term momentum and potential trend continuation zones.

---

## ✨ Features

* 📈 Detects 5 bullish candles in a row
* 📉 Detects 5 bearish candles in a row
* 🏷️ Visual signals plotted directly on chart
* ⚡ Lightweight and fast execution
* 🎯 Works on all timeframes

---

## 📜 Indicator Logic

The script checks the last 5 candles:

* **Bullish Condition (5 Green Candles):**

  * Each candle closes above its open

* **Bearish Condition (5 Red Candles):**

  * Each candle closes below its open

---

## 📍 Signals

* 🟢 **"5G" Flag below candle** → 5 consecutive bullish candles
* 🔴 **"5R" Circle above candle** → 5 consecutive bearish candles

---

## 🛠️ How to Use

1. Open TradingView
2. Go to **Pine Editor**
3. Copy the script from this repository
4. Paste it into the editor
5. Click **Add to Chart**

---



## 📌 Notes

* Works best in trending markets
* Can be combined with support/resistance or indicators like EMA
* Signals do not guarantee reversal or continuation

---

## ⚠️ Disclaimer

This indicator is for educational purposes only.
Not financial advice. Always test before live trading.

---

## 📜 License

MIT License
