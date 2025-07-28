# Big Data University Project - COVID-19 Travel & Mobility Analysis

## Overview
This repository contains a comprehensive big data analysis project focused on COVID-19 travel and mobility patterns. The project analyzes large-scale travel data to understand how people's movement patterns changed during the pandemic, including stay-at-home behaviors and trip distances across different geographic levels (National, State, County).

## Project Structure
```
5011-big-data/
├── Bigdataprject.ipynb    # Main Jupyter notebook with COVID-19 travel analysis
├── README.md              # This file
├── requirements.txt       # Python dependencies
└── .gitignore           # Git ignore rules
```

## Dataset Analysis
The project analyzes two main datasets:
- **Trips_by_Distance.csv**: Contains detailed trip distance data with geographic breakdowns
- **Trips_Full Data.csv**: Comprehensive travel data with additional metrics

### Key Features Analyzed:
- **Population Staying at Home**: Analysis of stay-at-home patterns by week/month
- **Trip Distance Categories**: 
  - <1 mile trips
  - 1-3 mile trips
  - 3-5 mile trips
  - 5-10 mile trips
  - 10-25 mile trips
  - 25-50 mile trips
  - 50-100 mile trips
  - 100-250 mile trips
  - 250-500 mile trips
  - 500+ mile trips
- **Geographic Analysis**: National, State, and County level data
- **Temporal Patterns**: Weekly and monthly trends

## Analysis Components

### 1. Data Preprocessing
- Data cleaning and null value handling
- Date conversion and formatting
- Geographic data standardization
- Data aggregation by time periods

### 2. Exploratory Data Analysis
- **Stay-at-Home Patterns**: Analysis of population staying home by week
- **Trip Distance Distribution**: Bar charts showing travel patterns by distance
- **Scatter Plots**: Visualization of trips 10-25 miles vs 50-100 miles over time
- **Geographic Trends**: County and state-level mobility patterns

### 3. Big Data Processing with Dask
- Parallel processing implementation
- Performance comparison with different processor counts (10 vs 20 processors)
- Distributed computing for large dataset handling

### 4. Machine Learning Models
- **Linear Regression**: Predicting trip patterns
- **Polynomial Regression**: Non-linear relationship modeling
- **Advanced Linear Models**: Using statsmodels for detailed statistical analysis
- **Random Forest Classifier**: Classification of travel patterns

### 5. Statistical Analysis
- Coefficient of determination (R²) calculations
- Model performance evaluation
- Predictive modeling for travel behavior
- Statistical significance testing

## Key Visualizations
- Bar charts showing population not staying at home by distance traveled
- Scatter plots of trip patterns over time
- Geographic heatmaps of mobility patterns
- Time series analysis of stay-at-home trends

## Technologies Used
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib/Seaborn**: Data visualization
- **Dask**: Distributed computing for big data
- **Scikit-learn**: Machine learning algorithms
- **Statsmodels**: Advanced statistical modeling
- **Jupyter Notebook**: Interactive development environment

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required Python packages (install via pip):
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn dask dask-ml statsmodels
  ```

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Nwachukwu1300/big-data-uni-proj.git
   cd big-data-uni-proj
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
Open `Bigdataprject.ipynb` in Jupyter Notebook to view and run the COVID-19 travel analysis. The notebook contains:

1. **Data Loading and Preprocessing**: Import and clean the travel datasets
2. **Exploratory Analysis**: Understand patterns in stay-at-home behavior and trip distances
3. **Big Data Processing**: Use Dask for efficient processing of large datasets
4. **Machine Learning**: Implement various models to predict travel patterns
5. **Visualization**: Create charts and graphs to illustrate findings

## Key Findings
- Analysis of how COVID-19 affected travel patterns
- Comparison of short vs long-distance travel trends
- Geographic variations in stay-at-home compliance
- Predictive models for future travel behavior

## Course Information
- **Course**: Big Data (5011)
- **Institution**: University Course
- **Project Focus**: COVID-19 Travel and Mobility Data Analysis

## Author
**Nwachukwu1300**
- GitHub: [@Nwachukwu1300](https://github.com/Nwachukwu1300)

---

*Last updated: December 2024* 