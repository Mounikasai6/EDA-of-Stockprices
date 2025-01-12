# Financial Data Visualization Project

## Overview
This project demonstrates various visualization techniques using historical financial market data. The visualizations are created using Python's popular data visualization libraries including Matplotlib, Seaborn, and Plotly.

## Features
- Multiple visualization types:
  - Bar Charts
  - Line Plots
  - Heatmaps
  - Scatter Plots
  - Pie Charts
  - Histograms

## Dataset
- Source: [Kaggle - EDA of Stock Prices Financial Crisis](https://www.kaggle.com/code/tomasmantero/eda-of-stock-prices-financial-crisis/input)
- Dataset contains historical financial market data
- Five CSV files concatenated for comprehensive analysis

## Requirements
python
matplotlib
seaborn
plotly
pandas
numpy


## Installation
bash
# Clone the repository
git clone https://github.com/Mounikasai6/EDA-of-Stockprices.git

## Usage
python
# Import required libraries
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px

# Load the data
data = pd.read_csv('your_file.csv')

# Create visualizations
# Example: Line Plot
plt.figure(figsize=(12, 6))
plt.plot(data['Date'], data['Close'])
plt.title('Stock Price Over Time')
plt.show()


## Visualization Types and Their Uses

### 1. Line Plots
- Track stock prices over time
- Visualize market trends
- Compare multiple stocks

### 2. Bar Charts
- Compare values across categories
- Show volume analysis
- Display periodic returns

### 3. Heatmaps
- Correlation analysis
- Market sector relationships
- Trading volume patterns

### 4. Scatter Plots
- Relationship between variables
- Risk vs. Return analysis
- Correlation visualization


### 7. Pie Charts
- Market sector distribution
- Portfolio allocation
- Asset class breakdown

### 8. Histograms
- Return distributions
- Volume analysis
- Price frequency distribution

## Contributing
1. Fork the repository
2. Create your feature branch 
3. Commit your changes 
4. Push to the branch
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Data source: Kaggle
- Python data visualization community
- Contributors and maintainers of Matplotlib, Seaborn, and Plotly

## Contact
Project Link: https://github.com/Mounikasai6/EDA-of-Stockprices
