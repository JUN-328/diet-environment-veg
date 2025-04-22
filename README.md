# diet-environment-veg
# Environmental Impact by Diet Type and Gender

This project visualizes and compares the environmental impact of six diet groups across five ecological indicators, split by gender. The visualization includes both static radar charts and an interactive web version.

---

# Project Contents

| File | Description |
|------|-------------|
| `radar_analysis_project.ipynb` | Notebook: data processing, normalization, static radar chart. Matrix: 12 radar charts showing individual diet × gender patterns with values|
| `html_code.ipynb` | Fully interactive radar chart (Plotly) — open in any browser to explore group differences |
| `radar_chart.png` | This radar chart displays the normalized environmental impact of six diet groups (vegan to high meat-eater), separately for males and females.Each line represents one group, with male groups in solid lines and female groups in dashed lines.The chart compares five key ecological indicators: GHG emissions, land use, water use, eutrophication, and biodiversity|
| `radar_matrix_grid_with_labels.png` |This subplot matrix contains 12 individual radar charts, each representing one combination of diet group and gender.Each panel is clearly labeled, and the chart includes exact normalized values on each axis point |
| `interactive_radar_chart.html` | A fully interactive radar chart built using Plotly.Users can hover to view detailed values, toggle visibility of specific groups using the legend, and zoom/pan the radar space|
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
