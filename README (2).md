# Seaborn Data Visualization

This repository contains a Jupyter Notebook (`seaborn.ipynb`)
demonstrating data visualization in Python using **Seaborn** and
**Matplotlib**.

## Project Overview

Seaborn is a Python data visualization library built on top of
Matplotlib. It makes it easier to create attractive statistical graphics
and explore patterns in datasets.

In this notebook, the Seaborn **Iris** dataset is used to practise
different types of plots and understand how to visualize numerical and
categorical data.

## Technologies and Libraries

-   Python
-   Jupyter Notebook
-   Seaborn
-   Matplotlib
-   Pandas
-   NumPy

## Installation

Install the required libraries using pip:

``` bash
pip install seaborn matplotlib pandas numpy
```

## Import Libraries

``` python
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd
import numpy as np
```

## Dataset

The notebook uses Seaborn's built-in Iris dataset:

``` python
df = sns.load_dataset("iris")
```

The dataset contains measurements of iris flowers, including:

-   `sepal_length`
-   `sepal_width`
-   `petal_length`
-   `petal_width`
-   `species`

The `species` column identifies the flower species.

## Topics Covered

The notebook includes examples and practice with:

1.  **Dataset exploration** --- viewing the dataset, displaying the
    first and last rows, finding unique species, and counting category
    values.
2.  **Line plot** --- exploring the relationship between sepal
    measurements and viewing lines by species.
3.  **Scatter plot** --- comparing sepal and petal measurements, with
    species shown using different colours.
4.  **Bar plot** --- comparing average sepal length across species.
5.  **Count plot** --- counting the observations in each species
    category.
6.  **Box plot** --- viewing the distribution, median, quartiles,
    spread, and possible outliers.
7.  **Violin plot** --- examining distributions and density across
    species.
8.  **Strip plot** --- displaying individual observations for
    categories.
9.  **Histogram** --- viewing the frequency distribution of petal width.
10. **KDE (Kernel Density Estimation)** --- adding a smooth density
    curve to a histogram.
11. **Distribution plot (`distplot`)** --- practising a univariate
    distribution plot. Note: `distplot` is deprecated in newer Seaborn
    versions; `histplot` and `kdeplot` are the recommended alternatives.
12. **Pair plot** --- exploring pairwise relationships between numerical
    variables.
13. **Categorical plots (`catplot`)** --- practising violin and swarm
    plot kinds.
14. **Correlation heatmap** --- visualizing correlations between
    numerical columns using colours and annotations.

## How to Run

1.  Clone or download this repository.
2.  Open the project folder in Jupyter Notebook or JupyterLab.
3.  Open `seaborn.ipynb`.
4.  Run the cells from top to bottom.

## Learning Objectives

After working through this notebook, you should be able to:

-   Load and inspect a Seaborn dataset.
-   Identify when to use common visualization types.
-   Compare numerical measurements across categories.
-   Explore distributions and possible outliers.
-   Understand relationships and correlations between numerical
    variables.
-   Create visualizations using Seaborn and Matplotlib.

## Repository Structure

``` text
.
├── README.md
└── seaborn.ipynb
```

## Note

This is a learning and practice notebook. It contains examples of
different Seaborn visualizations using the Iris dataset.
