# Review Scraper
Scrapes Google for product reviews and runs sentiment analysis on result descriptions

LIVE at [reviewscrper.streamlit.app](https://reviewscrper.streamlit.app/)!

## What it uses
 - *Huggingface* for sentiment analysis
    - Uses `LiYuan/amazon-review-sentiment-analysis` for 1-5 star rating
    - Uses `cardiffnlp/twitter-roberta-base-sentiment-latest` for positive/neutral/negative
 - *Apify* for scraping Google
 - *Streamlit* for hosting the website
 - *WordCloud* for word clouds

## Demo
TIP: Be specific e.g. `PS5 console` not `PS5`


## References
 - Inspired by [nus-sentiment](https://github.com/nus-sentiment/nus-sentiment)


