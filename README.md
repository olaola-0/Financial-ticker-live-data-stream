# Comprehensive Financial Market Analysis: Static and Streaming Data

This repository hosts two Jupyter notebooks, `static_data.ipynb` and `streaming_data.ipynb`, designed for comprehensive financial market analysis using both static and live streaming data. These notebooks employ advanced techniques, such as Bollinger Bands and Volume Weighted Average Price (VWAP), to offer deep insights into stock trends, market behaviors, and trading strategies, complete with actionable buy, sell, hold, and alert signals.

## Visualization Examples

Below are some examples of the visualizations and trade signal outputs produced by the notebooks:

### Bollinger Bands with Trading Signals
![20 minutes Bollinger bands with last 1 minute average](images/Screenshot%202024-03-07%20at%2016.59.01.png)

This visualization from `static_data.ipynb` shows the Bollinger Bands calculated over a 20-minute window with the last 1-minute average price. The colored dots represent different trade signals: red for sell, green for buy, and grey for hold.

### VWAP with Trade Actions
![VWAP and trade actions](images/Screenshot%202024-03-07%20at%2016.59.42.png)

A snippet from the output table in `static_data.ipynb` presenting the calculated VWAP values along with corresponding trade actions based on the analysis.

### Real-Time Streaming Data Analysis
![10 minutes Bollinger bands with the last 1 minute average in streaming mode](images/Screenshot%202024-03-07%20at%2017.00.17.png)


## Notebooks Overview

### Static Data Analysis (`static_data.ipynb`)

Focuses on the analysis of historical financial data to extract meaningful insights and trends. It includes detailed explorations of Bollinger Bands and VWAP for static market data, providing a solid foundation for understanding stock movements and volatility. This notebook is perfect for in-depth market research and historical trend analysis.

Key Features:
- Data preparation and transformation for analysis.
- Sliding window analysis for computing statistical summaries.
- Generating buy, sell, and hodl signals based on historical data.
- Visualizations including Bollinger Bands and VWAP to illustrate market trends.

### Real-Time Data Analysis (`streaming_data.ipynb`)

Designed for live market data analysis, this notebook offers tools to process and visualize data in real-time. It supports live data streaming and interactive visualizations, enabling users to monitor market trends and make informed trading decisions on the fly.

Key Features:
- Integration with live financial ticker data for real-time analysis.
- Application of Bollinger Bands and VWAP in a streaming context.
- Real-time generation of buy, sell, and hodl alerts.
- Dynamic and interactive data visualizations to track market movements.

## Data

The analysis in both notebooks is exemplified using `ticker.csv`, a dataset containing sample financial market data. This CSV file provides a practical basis for demonstrating the analysis techniques and generating trading signals.

## Getting Started

1. Clone this repository to access the notebooks and the `ticker.csv` data file.
2. Install Jupyter Notebook or JupyterLab, along with required Python packages such as Pandas, NumPy, and visualization libraries like Matplotlib or Bokeh.
3. Launch the desired notebook in Jupyter and follow the instructions within to perform the analysis.

## Contributing

Contributions are welcome! If you have ideas for improving the analysis, adding new features, or enhancing the visualization aspects, please fork the repository, implement your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Credit 
```
pathway
```
