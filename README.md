Market Sentiment Analysis
This project analyzes the relationship between market sentiment and cryptocurrency trading performance. It uses historical trading data and the Fear & Greed Index to generate insights into how different market moods—Fear, Greed, and Neutral—correlate with trading profitability and volume.

Files
* financial_sentiment_analysis.py: The core Python script that performs the data cleaning, analysis, and visualization. It reads the provided CSV files, merges the data, analyzes it, and generates the plots.

* fear_greed_index.csv: Contains the historical Fear & Greed Index data.

* historical_data.csv: Contains historical cryptocurrency trading data.



How to Run the Project
To run the analysis, you'll need Python and the following libraries installed:

* pandas

* matplotlib

* os

* numpy

You can install these using pip:
pip install pandas matplotlib numpy

Once the dependencies are installed, you can execute the Python script from your terminal:
python financial_sentiment_analysis.py

Output
The script will:

* Generate and save a new CSV file, sentiment_analysis.csv, in the csv_files directory. This file contains the summarized analysis of profitability and volume by sentiment.

* Create and save two image files in the outputs directory:

* pnl_by_sentiment.png: A bar chart showing the average profit/loss (PnL) for each sentiment type.

* volume_by_sentiment.png: A bar chart showing the total trading volume for each sentiment type.

* Display the generated plots.

Conclusion
This analysis serves as a great starting point for understanding the impact of market psychology on trading results. The generated report and visualizations can be used for further study or to inform trading strategies.
