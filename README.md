# Assignment 10

**Name:** Natalie Hlusi  
**Course:** CS 490 — Data Visualization  
**Aiming for Grade:** A  

**Website:** https://natyhl.github.io/dataviz_assignment10/  
**Repository:** https://github.com/natyhl/dataviz_assignment10  
**Dataset:** https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset  

---

## About

This project explores how data visualizations can be made misleading through wrong choice of design ctechniques. The narrative falsely claims that more physical activity leads to less sleep, supported by a modified dataset and different modified charts.

---

## Interactive Charts

Deceptive vs. ethical chart comparison visible on: https://natyhl.github.io/dataviz_assignment10/ 

- `manipulation_techniques.html` — deceptive chart with 3 manipulation techniques and manipulation analysis
- `line_chart.html` — ethical D3 line chart
- `bar_ethical.html` — ethical remake of the real-world misleading Console bar chart

---

## Data Modification

42 rows were removed from the low physical activity group — participants with activity below 40 min/day who reported sleep durations of 5.8–6.8 hours.

- Original: 74 people, average sleep = 7.11 hrs
- Modified: 32 people, average sleep = 8.43 hrs

Both the original (`Sleep_health.csv`) and modified (`Sleep_health_modified.csv`) datasets are included in the repository.

---

## Manipulation Techniques

1. Cherry picking — only Low and Moderate activity groups shown, hiding Active and Very Active
2. Truncated Y-axis — axis starts at 6.0 instead of 0
3. Misleading smoothing — Trend line applied to hide spread of answers