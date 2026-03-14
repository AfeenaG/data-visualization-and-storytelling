# Interactive Redesign of Florence Nightingale's Visualization Project Overview

This project recreates and modernizes Florence Nightingale’s famous Coxcomb chart, one of the earliest examples of data visualization used to influence public policy.

Florence Nightingale originally developed this radial diagram in the 1850s to demonstrate that most soldier deaths during the Crimean War were caused by preventable diseases rather than battlefield injuries. Her visualization played a key role in advocating for improved hospital sanitation and public health practices.

In this project, the historical visualization was recreated and extended into an interactive dashboard, allowing users to dynamically explore the data through filters and interactive chart elements.

[![Watch the video](https://img.youtube.com/vi/VsfQ-0FbqDw/0.jpg)](https://youtu.be/VsfQ-0FbqDw)

# Project Goals

The main objectives of this project were to:

Recreate Nightingale’s Coxcomb (polar area) chart

Explore how historical visualizations can be modernized with interactivity

Design a dashboard interface for exploring mortality data

Demonstrate how interactive features can improve data exploration and user engagement

# Interactive Features

The visualization is deployed through a Flask-based web application and includes several interactive components.

Data Filtering

Users can filter the dataset using a dropdown menu that allows selection by:

- Year

- Cause of death

This enables users to explore how mortality patterns change across time and categories.

- Hover Interactions

- Hovering over chart segments reveals additional details, including:

- Cause of death

- Year

- Number of recorded deaths

These tooltips provide deeper context without cluttering the main visualization.

Clickable Chart Segments

Users can click on sections of the radial chart to generate a corresponding line visualization displayed below the main chart.

The line length is proportional to the number of deaths associated with the selected category, allowing users to quickly compare relative magnitudes.

Visualization Preview
Radial (Coxcomb) Chart




Interactive Dashboard




Hover Interaction Example


# Technologies Used

This project combines several technologies to implement the interactive visualization.

- Python

- Flask

- Jupyter Notebook

- Interactive visualization libraries

- HTML / CSS

The data processing and visualization logic were developed in a Jupyter Notebook before being integrated into a web-based dashboard.

# Project Structure
```02-florence-nightingale-interactive-visualization
├── README.md
├── Notebooks/
│   └── florence_nightingale_chart.ipynb
└── flask/
    ├── app.py
    └── templates/
        ├── index.html
        └── nightingale_chart.html```

</pre>

# Key Learning Outcomes

This project reinforced several important visualization and design concepts.

Historical Visualizations Still Matter

Classic visualizations such as Nightingale’s Coxcomb chart remain powerful examples of how data can influence policy decisions.

Interactivity Improves Data Exploration

Interactive dashboards allow users to:

- filter data

- explore categories

- uncover patterns independently

This makes visualizations more engaging and informative.

Design Matters as Much as Data

Effective visualizations require careful attention to:

- layout

- color encoding

- user interaction

- clarity of message

Why This Visualization is Important

Florence Nightingale’s work represents one of the earliest examples of data-driven advocacy.

By modernizing her visualization, this project demonstrates how historical data storytelling techniques can be enhanced using modern tools to support interactive data exploration and education.

# Author

Afeena G: Graduate Student – Business Analytics and Artificial Intelligence

This project is part of my academic portfolio demonstrating skills in:

- data visualization

- interactive dashboard design

- analytical storytelling
