# Stock Market Analysis

## Introduction
This repository contains the code and analysis for the project "Stock Market Prediction and Sentiment Analysis". This project aims to predict stock market movements by analyzing sentiment data derived from news headlines alongside historical stock price data.

## Project Structure
- `src`: Contains all the source code.
- `stock-market-prediction-and-sentimental-analysis`: Directory for scripts and notebooks used in the analysis.

## Dataset Description
The dataset used in this project comes from Kaggle and encompasses a period from 2008 to 2015. It consists of two main types of data:

### News Data
- **Source:** Reddit news headlines, ranked by Reddit users.
- **Range:** June 8, 2008, to July 1, 2015.
- **Description:** The dataset includes the top 25 ranked news headlines for each date, reflecting the most significant news events according to Reddit's userbase.

### Stock Data
- **Source:** Dow Jones Industrial Average (DJIA)
- **Range:** August 8, 2008, to July 1, 2015.
- **Description:** This data is used to "prove the concept" of stock market prediction based on the news sentiment.

#### Files
- `Combined_News_DJIA.csv`: Contains news ranked from top to bottom for each date.
- `RedditNews.csv`: Contains the top 25 news headlines for each date.
- `DJIA_table.csv`: Contains stock price data including opening, closing, high, low, and volume.
- `Test_dates.csv`: Contains dates for which predictions are to be made.
- `sample_submission.csv`: Format for submissions.

#### Columns in Detail
- `Date`: The date on which the news is published or the stock data is recorded.
- `Label`: Binary indicator (1 or 0); '1' indicates the DJIA Adj Close value rose or stayed the same, '0' indicates it decreased.
- `Top1 to Top25`: News headlines ranked from most to least significant on that particular date.
- `Open`, `High`, `Low`, `Close`, `Volume`, `Adj Close`: Metrics describing the stock performance on a given day.

## Usage
To replicate the analysis or to use this data for further experimentation, follow the instructions provided in the respective scripts and notebooks. Ensure all dependencies are installed as specified in the `requirements.txt` file (to be added if necessary).

## License
MIT License

Copyright (c) 2024 Harshvardhan Joshi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
