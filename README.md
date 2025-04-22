# diet-environment-veg
# Environmental Impact by Diet Type and Gender

This project visualizes and compares the environmental impact of six diet groups across five ecological indicators, split by gender. The visualization includes both static radar charts and an interactive web version.

---

# Project Contents

| File | Description |
|------|-------------|
| `radar_analysis_project.ipynb` | Main notebook: data processing, normalization, static radar chart, and Plotly interactive chart |
| `radar_matrix_refined.ipynb` | Subplot matrix: 12 radar charts showing individual diet × gender patterns with values |
| `interactive_radar_chart.html` | Fully interactive radar chart (Plotly) — open in any browser to explore group differences |
| `radar_chart.png` | 
| `radar_matrix_grid_with_labels.png` | 
| `interactive_radar_chart.html` | 
---

#  Indicators Visualized

- Greenhouse gas emissions (GHG)
- Land use
- Water use
- Eutrophication potential
- Biodiversity impact

---

#  Features

- Radar chart comparing normalized environmental impacts for:
  - 6 diet groups: Vegan, Vegetarian, Fish, Low, Medium, High meat-eaters
  - Gender: Male and Female
- Interactive HTML file supports:
  - Hover tooltips
  - Clickable legend to toggle visibility
  - Zoom and pan support

---

# Insights Enabled

- Vegan diets show the lowest overall environmental impact  
- High meat-eaters show the highest in all dimensions  
- Gender consistently affects results — females generally score lower  
- Even partial meat reduction (e.g., from High to Medium) yields meaningful gains

---

#  Data Source
Based on the EPIC-Oxford dietary dataset (normalized).
Preprocessed version provided: Results_21MAR2022_nokcaladjust.csv

---
# Author
Jun Jiang
Course: COMP4037 – Research Methods
Nottingham University, 2025
