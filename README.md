# Trader Behavior Insights  Market Sentiment vs Trader Performance

  Objective
To explore how trader performance (PnL, leverage, trade size, etc.) relates to market sentiment phases (fear/greed), uncover hidden patterns, and deliver actionable insights that can drive smarter trading strategies.



  Datasets
1. Bitcoin Market Sentiment Dataset
   - Columns: 'Date', 'Classification (Fear/Greed)'
   - Provides the sentiment phase for each date.

2. Historical Trader Data (Hyperliquid)
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.
   - Provides execution-level data on trades.


 Methods
- Data preprocessing & feature engineering  
- Time alignment of trades with sentiment index  
- Descriptive statistics & exploratory visualizations  
- Hypothesis testing (Mann–Whitney U, correlation checks)  
- Regression analysis (OLS with account fixed effects)  
- Aggregation of trader level performance by sentiment phases  

 Key Findings (sample)
1. Market sentiment correlates with aggregated PnL distributions.  
2. Fear phases often show smaller notional sizes and lower leverage.  
3. Certain accounts consistently adapt their strategies across sentiment regimes.  


 How to Run
1. Clone the repository:
 git clone  https://github.com/PranithaBokketi/Trade-behaviour-analysis

Install dependencies:
pip install -r requirements.txt

Place the datasets in the project directory:

historical_data.csv

fear_greed_index.csv

Run the notebook:
jupyter notebook notebook.ipynb

Deliverables

Exploratory analysis & visualizations

Statistical tests & regression models

6-slide summary (PDF) covering:

Objective

Datasets

Methods

3 Key Findings

Recommendations

Next Steps

Tech Stack :

Python (pandas, numpy, matplotlib, seaborn)

statsmodels, scipy, scikit-learn

Jupyter Notebook



  
