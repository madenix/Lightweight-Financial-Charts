## ​📈 Lightweight Financial Charts Examples

A collection of fundamental and advanced examples demonstrating how to implement financial charts using the **TradingView Lightweight Charts** library.

⚠️ This repo uses CDN link. You need to use `LightweightCharts` object to access library 

## ✨ Key Features of Lightweight Charts

This repository leverages the following core strengths of the TradingView Lightweight Charts library:

* **Extremely Lightweight:** At only **~35 KB**, it ensures fast loading times and superior performance, even on mobile devices.
* **Powerful:** Designed specifically for displaying financial data (OHLC, volume, etc.).
* **Free to Use:** A robust, open-source solution for web-based charting.
* **Mobile-Friendly:** Charts are responsive and work seamlessly across all screen sizes.

## 📁 Repository Structure and Examples

This repository serves as a quick-start guide, providing ready-to-run HTML files for the most common chart types.

| File Name | Chart Type | Description |
| :--- | :--- | :--- |
| `BasicLineChart.html` | Line Chart | A fundamental example of displaying time-series data with a simple line. |
| `BasicAreaChart.html` | Area Chart | Demonstrates a line chart with a filled area below the curve. |
| `BasicCandleSticks.html` | Candlestick Chart | **Essential for finance.** Shows the Open, High, Low, and Close (OHLC) values. |
| `BasicHistogramChart.html` | Histogram Chart | Ideal for visualizing volume data or other single-value metrics. |

## ⚙️ Getting Started

Follow these simple steps to run the examples locally.

### Prerequisites

You only need a web browser to view these examples

#### 1.Clone the repository

```
git clone https://github.com/madenix/Lightweight-Financial-Charts.git
```

#### 2.Run the examples
- Navigate into the cloned directory
- Open any *.html file (e.g., BasicCandleSticks.html) directly in your web browser

## ​💡 Understand structure

Since the library is loaded via CDN, the entire charting functionality is exposed through the global `LightweightCharts` object. You can verify this by opening your browser's Developer Tools (F12) and typing `window` into the console.

<img width="738" height="656" alt="LightweightChartsMethods" src="https://github.com/user-attachments/assets/e11022a4-82a1-49d4-b977-18a5133e213a" />
