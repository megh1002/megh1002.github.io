---
layout: default
title: Building Inventory Data Visualization
---

# Building Inventory Data Visualizations

## Chart 1: Building Size vs. Number of Stories (Interactive)

This chart visualizes the relationship between **Square Footage** (on the x-axis) and **Total Floors** (on the y-axis) of buildings. The data points are color-coded by **Year Constructed**, which helps to observe trends across different time periods.


<iframe src="charts/chart1.html" width="100%" height="500" style="border:none;"></iframe>


---

## Chart 2: Average Building Size by Number of Stories (Interactive)

This chart displays the average Square Footage of buildings based on the number of Total Floors. The bars represent the mean square footage for buildings with a specific number of floors. This helps identify how the building size varies across different numbers of stories.

<iframe src="charts/chart2.html" width="100%" height="500" style="border:none;"></iframe>

---

## Interactivity

Chart 1: The first chart includes interactivity where the user can select a Year Constructed from the legend to highlight buildings built in that specific year. This allows users to focus on buildings from particular years, making it easier to identify trends or patterns over time.

Chart 2:  The second chart is interactive using an interval selection (brush), which allows users to zoom in on specific bars based on the number of Total Floors. This makes it easier to explore the average square footage for buildings with fewer or more floors.


---

## Homework 5 Overlap

For this assignment, I used similar visualizations from Homework #5, where I analyzed the Building Inventory dataset, but I made improvements to the interactivity. In Homework #5, the visualizations did not have interactive features, whereas in this assignment, I added selection-based interactivity for highlighting specific data points in Chart 1 and interval selection for zooming in on bars in Chart 2. These adjustments make the visualizations more engaging and allow users to better explore the data.

---

## View the Data and Notebook

- [The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv  )
- [The Analysis](https://github.com/megh1002/megh1002.github.io/blob/main/Workbook.ipynb)