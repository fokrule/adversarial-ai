Stock Data Anomaly Detection
Overview
This project is a data analysis pipeline built in Python to perform exploratory analysis on S&P 500 stock data. The primary goal is to identify and analyze unusual trading activity, such as significant spikes in volume or value, which could indicate market anomalies. This script provides the foundation for a more in-depth time-series analysis.
Features
 * Data Ingestion: Efficiently loads stock data from a CSV file using the pandas library.
 * Data Inspection: Prints essential information about the dataset, including data types and total number of records.
 * Descriptive Statistics: Calculates and displays the average values for key numerical columns (NV_rand and VOLUME_rand).
 * Time-Series Processing: Converts the 'Time' column to a standard datetime format and identifies the start and end timestamps of the data.
Getting Started
Follow these steps to get a copy of the project up and running on your local machine.
Installation
This project requires Python and the pandas library.
 * Clone the repository:
   git clone https://github.com/fokrule/stock-data-anomaly-detection.git

 * Navigate to the project directory:
   cd stock-data-anomaly-detection

 * Install the required dependencies:
   pip install pandas

Usage
 * Ensure that the data file, VolumeAndNVbySymbol_wRand.csv, is located in the same directory as the script.
 * Open and run the adversarialai_project.ipynb Jupyter Notebook to execute the code and view the output.
Data
The analysis is performed on the VolumeAndNVbySymbol_wRand.csv dataset, which contains time-series data for various S&P 500 symbols, including:
 * Time: Timestamp of the data point.
 * SYMBOL_NAME: The ticker symbol for the stock.
 * NV_rand: A numerical value representing the net value.
 * VOLUME_rand: A numerical value representing the trading volume.
Future Enhancements
 * Anomaly Detection: Implement a statistical or machine learning-based anomaly detection algorithm (e.g., Z-score, Isolation Forest) to automatically flag unusual data points.
 * Visualization: Integrate data visualization libraries like Matplotlib or Seaborn to create plots of volume and value over time, highlighting detected anomalies.
 * Modular Code: Refactor the notebook into a more modular Python script (.py) to separate data processing and analysis logic.
License
This project is licensed under the MIT License - see the LICENSE file for details.
