# 🐧 Penguin Data Exploration: Reactive PyShiny App
✍️ Author
Lindsay Foster
Course: CINTEL-03 — Shiny for Python
Project: Reactive Filtering & Visualization

This project is a **reactive web application** built using **PyShiny** to explore the [Palmer Penguins dataset](https://allisonhorst.github.io/palmerpenguins/). It demonstrates filtering, visualizing, and exploring species and island data interactively in the browser.

---

## ✅ Project Goals

- Create a working Shiny for Python app using **PyShiny Express**.
- Load and explore the **Palmer Penguins** dataset.
- Use **reactive filtering** to update charts and tables based on user input.
- Visualize data using:
  - Plotly histograms
  - Seaborn histograms
  - Plotly scatterplots
  - Data table and grid
- Add user controls for selecting **species** and **islands**.
- Apply a **reactive `@reactive.calc` function** to dynamically filter data.
- Bonus: Add a chart to show **penguin count by species and island**.

---

## 📊 Features

### 🧩 Reactive Sidebar Inputs

- **Select Attribute** — Choose a numeric column (e.g. bill length).
- **Bin Count** — Set bin sizes for Plotly and Seaborn histograms.
- **Select Species** — Filter the data by penguin species.
- **Select Islands** — Filter by island location.

### 📈 Charts & Tables

- **Data Table** (filtered): Table view of species + island data.
- **Data Grid** (filtered): Grid-style data display.
- **Plotly Histogram**: Explore numeric features by species.
- **Seaborn Histogram**: Alt-style histogram with seaborn.
- **Plotly Scatterplot**: Visualize bill vs. flipper by species.
- **Bonus Histogram**: Count of penguins grouped by **species and island**.

---

## 🧠 Technologies Used

- `shiny` — Web app framework for Python
- `shinywidgets` — For enhanced plots (Plotly)
- `pandas` — Data manipulation
- `seaborn`, `matplotlib` — Data visualization
- `plotly.express` — Interactive plotting
- `palmerpenguins` — Dataset library

---

## 📂 Project Structure

cintel-03-reactive/
│
├── app.py # Main PyShiny app file
├── requirements.txt # App dependencies
├── README.md # Project summary and instructions


---

## 🚀 Running the App

You can test and edit this app in the [Shiny Playground](https://tinyurl.com/xesecvy3) 

### Online (Shiny Playground)
1. Copy `app.py` into [https://shinylive.io/py/](https://tinyurl.com/xesecvy3)
2. Click **▶ Run** to launch the app.

### Locally
```bash
pip install -r requirements.txt
shiny run --reload app.py

🔗 Links
GitHub Repo: https://github.com/LFoster03/cintel-03-reactive

Data Source: Palmer Penguins

Shiny for Python: https://shiny.posit.co/py/
