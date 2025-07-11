# Data Analysis with Pandas and Matplotlib

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kiruizz/data-analysis-pandas-matplotlib/HEAD?labpath=Analyzing%20data%20with%20pandas.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiruizz/data-analysis-pandas-matplotlib/blob/master/Analyzing%20data%20with%20pandas.ipynb)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/kiruizz/data-analysis-pandas-matplotlib/blob/master/Analyzing%20data%20with%20pandas.ipynb)

## 🌐 Live Demo Options
- **📊 Interactive Notebook**: Click the "Binder" badge above to run the notebook interactively in your browser
- **📱 Google Colab**: Click "Open in Colab" to run on Google's platform  
- **👀 Static View**: Click "nbviewer" to see a rendered version

## Project Overview
This repository contains a comprehensive Jupyter notebook demonstrating data analysis techniques using Python's pandas library and data visualization with matplotlib.

## Objectives
- Load and explore datasets using pandas
- Perform basic data analysis operations
- Create various types of visualizations with matplotlib and seaborn
- Handle errors and missing data appropriately

## Datasets Used
- **Iris Dataset**: Famous classification dataset from scikit-learn
- **Synthetic Sales Data**: Generated time-series data for demonstration

## Key Features
✅ **Data Loading & Exploration**
- Error handling with try-except blocks
- Dataset structure analysis
- Missing value detection and cleaning

✅ **Statistical Analysis**
- Descriptive statistics using `.describe()`
- Groupby operations and aggregations
- Correlation analysis

✅ **Data Visualizations**
- **Line Charts**: Time series trends and moving averages
- **Bar Charts**: Category comparisons and grouped data
- **Histograms**: Distribution analysis with multiple styles
- **Scatter Plots**: Relationship exploration and clustering

## Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Dataset loading

## File Structure
```
Data Analysis/
├── Analyzing data with pandas.ipynb    # Main analysis notebook
├── README.md                          # Project documentation
└── sample_sales_data.csv             
```

## How to Run
1. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Analyzing data with pandas.ipynb"
   ```

3. Run all cells sequentially to see the complete analysis

## Key Insights
- Clear species differentiation in iris measurements
- Strong positive correlation between petal length and width (r ≈ 0.94)
- Distribution patterns reveal multimodal characteristics
- Effective visualization techniques for different data types

## Completion
This notebook successfully demonstrates all required tasks:
- ✅ Task 1: Dataset loading and exploration
- ✅ Task 2: Basic statistical analysis
- ✅ Task 3: Multiple visualization types
- ✅ Professional formatting and documentation

## 🚀 Making It Live - Advanced Options

### Option 1: Streamlit App (Interactive Dashboard)
Convert to a Streamlit app for a web dashboard:
```bash
pip install streamlit
# Create app.py from notebook
streamlit run app.py
```

### Option 2: Voilà (Notebook as Web App)
Turn the notebook into an interactive web app:
```bash
pip install voila
voila "Analyzing data with pandas.ipynb"
```

### Option 3: Deploy to Heroku/Railway
Deploy as a web application with these platforms for permanent hosting.

### Option 4: GitHub Pages + Jupyter Book
Create a professional documentation site:
```bash
pip install jupyter-book
jupyter-book create my-book
jupyter-book build my-book
```

## Author
Arnold Kirui

## Date
July 11, 2025
