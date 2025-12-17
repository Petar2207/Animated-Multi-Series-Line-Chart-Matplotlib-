# 📈 Animated Multi-Series Line Chart (Matplotlib)

This project creates a **smooth, time-based animated line chart** using **Matplotlib** and **NumPy**.  
It visualizes four data series across multiple years with interpolated motion, moving markers, and a pause at the final frame.

The animation can be:
- Displayed inline in **Jupyter Notebook**
- Exported as a **GIF**
- Exported as an **MP4 video**

---

## ✨ Features

- Smooth interpolation between yearly data points
- Multiple animated series with distinct styles
- Moving highlight markers for each series
- Custom grid, axis formatting, and background styling
- Configurable animation speed and pause duration
- Supports HTML5 video preview, GIF, and MP4 export

---

## 📊 Data Overview

The animation visualizes four example time series:

| Series | Description |
|------|------------|
| Series A | Steady long-term growth |
| Series B | Decline followed by recovery |
| Series C | Volatile pattern |
| Series D | Stable market leader |

Years displayed: **2018 – 2025**

---

## 🛠 Requirements

Make sure you have the following installed:

```bash
pip install numpy matplotlib
