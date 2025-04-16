# Cryptocurrency Price Analysis and Forecasting

## Project Description

This project is dedicated to collecting, analyzing, and forecasting the prices of the top 10 cryptocurrencies based on historical data, news sentiment, and technical indicators. Various machine learning and statistical methods are used to analyze time series and create forecasts for 2025.

### Project Steps:
1. **Data Collection**  
   - Collected the top 10 cryptocurrencies by market capitalization in the start of 2025.  
   - Gathered historical price data for cryptocurrencies during the same period.  
   - Collected headlines related to cryptocurrencies.

2. **Data Preprocessing**  
   - Cleaned the data by removing duplicates, missing values, and outliers.  
   - Standardized the data format.  
   - Synchronized the time series of prices and news data.  
   - Preprocessed text data (news headlines).

3. **Exploratory Data Analysis (EDA)**  
   - Plotted price graphs for each cryptocurrency.  
   - Analyzed correlations between currencies.  
   - Identified seasonality/trends in prices.  
   - Analyzed the relationship between prices and news.  
   - Plotted correlation matrices and perform time series decomposition.

4. **Sentiment Analysis**  
   - Preprocessed the text of news headlines.  
   - Applied sentiment analysis (positive, neutral, negative).  
   - Linked sentiment labels to dates.

5. **Feature Engineering**  
   - Combined price data and news sentiment into a single table.  
   - Created features like moving averages, RSI, volume, sentiment, etc.  
   - Applied feature engineering techniques: lags, rolling windows, indicators.

6. **Modeling**  
   - Selected and train models: ARIMA.  
   - Evaluated models using metrics such as RMSE and MAE.  
   - Used cross-validation to assess model stability.

7. **Forecasting**  
   - Used the best model to predict prices for 2025.  
   - Generated future price series.  
   - Estimated forecast confidence (confidence intervals).

8. **Results Visualization**  
   - Plotted predicted prices and compared them with historical trends.  
   - Created interactive visualizations for presenting results.

9. **Report / Presentation**  
   - Summarized model findings and insights about news impacts on cryptocurrencies.  
   - Documented insights: which cryptocurrencies are best for investment.  
   - Saved the Jupyter Notebook with results.

## Technologies Used

- **Python**: The main programming language for data analysis.
- **Pandas**: For data manipulation and feature creation.
- **Matplotlib / Seaborn / Plotly**: For data visualization.
- **Statsmodels**: For building the ARIMA model.
- **Scikit-learn**: For training machine learning models (Linear Regression).
- **TextBlob / VADER / transformers (HuggingFace)**: For sentiment analysis of news.
- **NLTK / SpaCy**: For text preprocessing.

## Installation

To run the project, you need to install some dependencies. Create and activate a virtual environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DataAnalysis3.git
   cd DataAnalysis3
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## How to Use

1. Open a Jupyter Notebook from the `notebooks/` folder and follow the instructions in the code. 
2. To work with data and train models, follow the steps described in each notebook.


## Notes

- The cryptocurrency data is collected using the CoinGecko and Binance APIs.
- News sentiment is analyzed using libraries such as TextBlob and VADER.
- ARIMA, Linear Regression, and LSTM models are used for price forecasting.

---

## Conclusion

This project provides a comprehensive approach to cryptocurrency analysis and forecasting, combining both classical statistical methods and modern machine learning techniques. It helps not only to analyze the impact of news and trends but also to generate long-term price predictions for the cryptocurrency market.
