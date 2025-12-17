# 📈 Animated Line Graphs (Matplotlib · Jupyter Notebook)

This repository contains **animated line graph examples** built with **Matplotlib** and **NumPy**, designed for **presentation-ready data visualizations** in **Jupyter Notebook**.

The notebooks demonstrate two versions of the same animated line chart:

1. A **standard 0–100 animated line graph**
2. An ** version with negative-value support and a forced bold zero line**

## 📂 Repository Contents
├── line_graph_100_animated.ipynb
└── hard_line_0__line_graph_100_animated.ipynb


---

## 1️⃣ `line_graph_100_animated.ipynb`

### Base Animated Line Graph

### Description
This notebook implements a **standard animated line chart** where values range from **0 to 100**.

### Features
- Smooth animated transitions between data points  
- Multiple data series  
- Styled markers and grid  
- Final-frame pause for emphasis  
- Clean, presentation-ready visuals  


## 2️⃣ `hard_line_0__line_graph_100_animated.ipynb`

### Animated Line Graph (Hard Zero Line)

### What Makes It Different
This version extends the base animation with **explicit zero-line handling**, solving a common Matplotlib limitation, categorical Timeline Version, One static data point revealed only at the final frame.

---

### ⭐ Key Advanced Features

#### ✅ Forced Bold Zero Line
- A **bold horizontal line at `y = 0` is always drawn**
- The zero line appears **even if `0` is not part of the axis tick range**
- Works even when:
  - Tick spacing skips zero (example: spacing of 20)
  - Data ranges from **−10 to +10**
  - Matplotlib would normally hide the zero line

This version extends the original animated line chart by introducing a
**categorical time axis**, **equal spacing between labels**, and a
**static data point that appears only at the final frame**.

It is designed for *years, months, quarters, or any non-numeric timeline*
where spacing must remain consistent regardless of label values.


---

## ▶️ How to Run

1. Open a notebook in **Jupyter**
2. Run all cells
3. View the animation inline
4. (Optional) Export as GIF or MP4 if enabled in the notebook


---

## 📜 License

MIT License — free to use, modify, and distribute.

