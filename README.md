# Experiment 1: Installation and Exploration of Python Libraries

## Aim

To download, install, and explore the features of **NumPy, SciPy, Jupyter, Statsmodels, Pandas, Matplotlib, Seaborn, Plotly, and Bokeh**.

## Objective

The objective of this experiment is to set up the Python data analytics environment and verify the installation of commonly used libraries for:

* Numerical computation
* Scientific computing
* Data manipulation
* Statistical analysis
* Data visualization
* Interactive visualization
* Jupyter-based development

## Software Requirements

* Python 3.x
* Jupyter Notebook / JupyterLab
* Command Prompt or Terminal

## Libraries Used

| Library     | Purpose                                  |
| ----------- | ---------------------------------------- |
| NumPy       | Numerical computing and array operations |
| SciPy       | Scientific and statistical computing     |
| Jupyter     | Interactive notebook environment         |
| Statsmodels | Statistical modeling and analysis        |
| Pandas      | Data manipulation and analysis           |
| Matplotlib  | Data visualization                       |
| Seaborn     | Statistical visualization                |
| Plotly      | Interactive data visualization           |
| Bokeh       | Interactive browser-based visualization  |

## Installation

Open **Command Prompt** and execute:

```bash
pip install numpy scipy jupyter statsmodels pandas matplotlib seaborn plotly bokeh jupyterlab
```

After installation, start Jupyter Notebook using:

```bash
jupyter notebook
```

Alternatively, JupyterLab can be started using:

```bash
jupyter lab
```

## Code Implementation

Create a new Python 3 notebook and execute the following code:

```python
# Import required libraries

import numpy as np
import pandas as pd
import matplotlib
import seaborn as sns
import statsmodels
import scipy
import plotly
import bokeh
import jupyterlab

# Display library versions

print("NumPy Version:", np.__version__)
print("SciPy Version:", scipy.__version__)
print("Pandas Version:", pd.__version__)
print("Matplotlib Version:", matplotlib.__version__)
print("Seaborn Version:", sns.__version__)
print("Plotly Version:", plotly.__version__)
print("Bokeh Version:", bokeh.__version__)
print("Statsmodels Version:", statsmodels.__version__)
print("JupyterLab Version:", jupyterlab.__version__)

print("\nAll required libraries imported successfully!")
```

## Output

Example output:

```text
NumPy Version: 1.23.5
SciPy Version: 1.9.3
Pandas Version: 1.5.2
Matplotlib Version: 3.6.2
Seaborn Version: 0.12.1
Plotly Version: 5.11.0
Bokeh Version: 3.0.3
Statsmodels Version: 0.14.0
JupyterLab Version: 3.5.0

All required libraries imported successfully!
```

> **Note:** Version numbers may vary depending on the Python environment and installation date.

## Features Explored

### NumPy

* Array creation
* Numerical operations
* Mathematical functions
* Statistical operations

### SciPy

* Scientific computing
* Statistical functions
* Probability distributions
* Mathematical analysis

### Pandas

* Series and DataFrames
* Data loading
* Data cleaning
* Data manipulation

### Matplotlib

* Line plots
* Bar charts
* Histograms
* Scatter plots

### Seaborn

* Statistical plots
* Distribution visualization
* Boxplots
* Pairplots

### Statsmodels

* Statistical models
* Regression analysis
* Hypothesis testing
* Statistical summaries

### Plotly

* Interactive charts
* Scatter plots
* Bar charts
* Interactive data visualization

### Bokeh

* Interactive plots
* Browser-based visualization
* Line and scatter plots
* Interactive dashboards

### Jupyter

* Interactive Python notebooks
* Code execution
* Output visualization
* Documentation using Markdown

## Result

The required Python libraries were successfully installed and imported. Their versions were verified using Jupyter Notebook. The basic purpose and features of **NumPy, SciPy, Jupyter, Statsmodels, Pandas, Matplotlib, Seaborn, Plotly, and Bokeh** were explored successfully.

## Conclusion

This experiment successfully established the Python environment required for **Data Analytics and Visualization**. The installed libraries provide a complete toolkit for numerical computation, data manipulation, statistical analysis, machine learning preparation, and static as well as interactive data visualization.

## Learning Outcome

After completing this experiment, the learner is able to:

* Install Python data analytics libraries.
* Launch and use Jupyter Notebook/JupyterLab.
* Import commonly used Python libraries.
* Check installed library versions.
* Understand the basic purpose of each library.
* Prepare the environment for subsequent DAV Lab experiments.


## Repository

This experiment is part of the **Data Analytics and Visualization (DAV) Lab** repository.
