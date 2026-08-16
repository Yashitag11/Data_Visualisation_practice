# Matplotlib Data Visualization

A practical Python notebook demonstrating different **data visualization techniques using Matplotlib, NumPy, Pandas, and SciPy**.

## 📌 Overview

This notebook provides hands-on examples of creating and customizing different types of plots. It starts with basic Matplotlib concepts and gradually explores statistical and data-analysis visualizations.

The notebook covers:

* Line graphs
* Legends and axes
* Bar charts
* Pie charts
* Histograms
* Skewed and normal distributions
* Scatter plots
* Correlation
* Box plots
* Heatmaps
* Missing-value visualization
* Density plots using KDE
* Comparing distributions
* Area charts
* Filled curves

## 🛠️ Libraries Used

The notebook uses the following Python libraries:

* **Matplotlib** – Creating and customizing visualizations
* **NumPy** – Numerical data and array operations
* **Pandas** – Working with structured/tabular data
* **SciPy** – Statistical analysis and Gaussian KDE

Install the required dependencies with:

```bash
pip install matplotlib numpy pandas scipy
```

## 📊 Visualizations Covered

### 1. Line Graph

Introduces basic line plotting using `plt.plot()` and demonstrates how x- and y-coordinate values can be visualized.

### 2. Legends and Axes

Demonstrates how to add:

* Legends
* Labels
* Multiple lines
* Different line styles
* Axis-related customization

### 3. Bar Chart

A bar chart is used to visualize student marks and compare values between students.

### 4. Pie Chart

A pie chart demonstrates the distribution of a monthly budget across categories such as:

* Home
* Self-care
* Transport
* Food
* OTT

### 5. Line Graph with Student Scores

A line graph is used to visualize CGPA across different semesters, including markers, grid lines, titles, and axis labels.

### 6. Histograms

The notebook demonstrates histograms for analyzing the distribution of student marks.

It also introduces:

* Mean
* Median
* Left-skewed distributions
* Right-skewed distributions
* Normal distributions
* Cumulative histograms

### 7. Scatter Plot

Scatter plots are used to visualize the relationship between two variables.

The notebook also calculates the **correlation coefficient** using NumPy.

### 8. Box Plot

Box plots are demonstrated for understanding data distribution and identifying potential outliers.

Examples include:

* A single dataset
* Data containing an outlier
* Comparison of two datasets
* Displaying means and outliers

### 9. Heatmaps

Heatmaps are introduced using `plt.imshow()`.

The notebook demonstrates:

* Basic heatmaps
* Correlation heatmaps
* Adding labels to cells
* Displaying correlation values
* Comparing subjects
* Visualizing missing values

### 10. Missing-Value Heatmap

A heatmap is used to represent missing and present values in a dataset.

The visualization uses:

* `1` = Missing
* `0` = Present

### 11. Density Plot / KDE

The notebook introduces **Kernel Density Estimation (KDE)** using `gaussian_kde` from SciPy.

It demonstrates how to:

1. Create a KDE from data.
2. Generate smooth x-values.
3. Plot the density curve.
4. Fill the area under the curve.
5. Compare distributions between two groups.

### 12. Area Chart

Area charts are demonstrated using monthly sales data.

The notebook also includes an example comparing the areas of two products over several months.

### 13. Fill Between Curves

The notebook demonstrates `plt.fill_between()` to fill the region between a curve and the x-axis.

A sine-wave example is used to illustrate this concept.

## 🎯 Learning Objectives

After working through this notebook, you should be able to:

* Create basic plots with Matplotlib.
* Work with NumPy arrays for visualization.
* Customize plot titles and axis labels.
* Add and configure legends.
* Create different types of statistical plots.
* Analyze distributions using histograms and KDE.
* Identify relationships between variables using scatter plots.
* Calculate and visualize correlations.
* Understand box plots and outliers.
* Create and interpret heatmaps.
* Visualize missing data.
* Compare multiple datasets visually.
* Create area charts and filled curves.

## 🚀 Getting Started

Clone or download the project and open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open the notebook and execute the cells sequentially.

Alternatively, the notebook can be opened using **JupyterLab**:

```bash
jupyter lab
```

## 📁 Project Structure

```text
.
├── matplotlib_data_visualization.ipynb
└── README.md
```

## 🧰 Requirements

* Python 3.x
* NumPy
* Pandas
* Matplotlib
* SciPy
* Jupyter Notebook or JupyterLab

## 📚 Purpose

This notebook is intended as a **practical learning resource for Python data visualization**. The examples focus on understanding how different plots can be used to represent numerical data, distributions, relationships, correlations, and trends.


