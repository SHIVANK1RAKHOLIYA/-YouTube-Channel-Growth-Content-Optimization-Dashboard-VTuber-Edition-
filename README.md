# -YouTube-Channel-Growth-Content-Optimization-Dashboard-VTuber-Edition-
A complete end-to-end data analytics and visualization project built in Python and Power BI to monitor, forecast, and optimize YouTube performance — tailored for VTubers and content creators.
📂 Project Structure
📁 data/
    ├── video_performance_data.csv
    ├── subscriber_data.csv
    ├── comments_data.csv
    ├── sentiment_wordcloud.csv
    ├── subscriber_forecast_lstm.csv
    └── weekly_sentiment_trend.csv

📁 notebooks/
    ├── sentiment_analysis.ipynb
    ├── subscriber_forecasting_lstm.ipynb

📁 powerbi/
    └── youtube_dashboard.pbix

📄 README.md

 How It Works
1. Data Simulation
-4 Channels: VTuber, Tech, Gaming, Education

-30 videos per channel (last 6 months)

-1,000 comments per channel

-Weekly subscriber data

2. Sentiment Analysis
-Cleaned and tokenized comments

-TF-IDF vectorization

-Naive Bayes classification (pseudo-labeled using TextBlob)

-Weekly sentiment trend output

3. Subscriber Forecasting
-LSTM model per channel

-Predicts next 4 weeks of subscriber growth

-Plots and CSV export with RMSE/MSE

4. Power BI Dashboard
-Top 5 videos by watch time

-Weekly sentiment trends

-Subscriber forecast (actual vs predicted)

-Word cloud (positive/negative keywords)

💡 Features
✅ Clean and reproducible data pipeline (Pandas)

✅ LSTM-based forecasting with TensorFlow

✅ TF-IDF + ML sentiment classifier

✅ Power BI-ready CSV exports

✅ Custom visuals: Word Cloud, CTR trends, Forecast KPIs
