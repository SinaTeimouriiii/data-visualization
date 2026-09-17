# Data Visualization

A collection of data visualization projects from *Python Crash Course* (3rd Edition) by Eric Matthes (Chapters 15–17).

This repository contains examples using **Matplotlib** and **Plotly**.

## Projects Included

| File                  | Description                              | Library    |
|-----------------------|------------------------------------------|------------|
| `mpl_squares.py`      | Simple line graph of squared numbers     | Matplotlib |
| `scatter_squares.py`  | Scatter plot of squared numbers          | Matplotlib |
| `random_walk.py`      | Random walk class                        | -          |
| `rw_visual.py`        | Visualizes a random walk                 | Matplotlib |
| `die.py`              | Die (dice) class                         | -          |
| `die_visual.py`       | Visualizes dice roll results             | Plotly     |


## Requirements

- Python 3.8 or higher
- Matplotlib
- Plotly

Install the required libraries:

```bash
pip install matplotlib plotly

How to Run
Open a terminal in the project folder and run any of the scripts:
Bashpython mpl_squares.py
python scatter_squares.py
python rw_visual.py
python die_visual.py

Project Structure
textdata_visualization/
├── mpl_squares.py       # Line graph example
├── scatter_squares.py   # Scatter plot example
├── random_walk.py       # RandomWalk class
├── rw_visual.py         # Random walk visualization
├── die.py               # Die class
└── die_visual.py        # Dice roll visualization (Plotly)

Notes

rw_visual.py requires random_walk.py in the same folder.
die_visual.py requires die.py in the same folder.
Plotly charts open in your default web browser.
You can modify the number of points or dice rolls in the scripts to experiment.


Credits
Based on the data visualization projects from:
Python Crash Course, 3rd Edition

by Eric Matthes

Published by No Starch Press

Happy visualizing!
