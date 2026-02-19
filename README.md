📌 Bitcoin Sentiment Analysis & Predictive Modeling


📊 Objective

This project analyzes Bitcoin market sentiment using the Fear & Greed Index and builds machine learning models to predict sentiment patterns and volatility behavior.

📂 Project Structure

bitcoin_sentiment_analysis.ipynb
fear_greed_index.csv
outputs/

⚙️ Methodology

Data preprocessing & time series sorting

Feature engineering (Rolling Mean & Rolling Std)

Random Forest (classification & regression)

KMeans clustering for sentiment regimes

📈 Key Insights

Sentiment shows persistence over short windows.

Volatility increases during extreme fear/greed regimes.

Rolling features improve model stability.

Regime detection helps identify risk phases.

💡 Strategy Recommendations

Reduce exposure during extreme fear spikes.

Use rolling volatility to adjust position sizing.

Apply regime detection before major allocation changes.

▶️ How to Run

pip install pandas numpy matplotlib scikit-learn
jupyter notebook bitcoin_sentiment_analysis.ipynb

📌 Author

Pina Solanki
