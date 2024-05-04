# Financial News Sentiment Analysis Project

## Overview
This project focuses on conducting sentiment analysis on financial news headlines and correlating the sentiment scores with stock price movements. The goal is to uncover actionable insights that can enhance financial forecasting accuracy and inform investment strategies.

## Project Structure
1. Data Collection and Preparation: Financial news datasets containing headlines, publication dates, and associated stock symbols are collected and prepared for analysis.
2. Sentiment Analysis: Natural Language Processing (NLP) techniques are employed to quantify the sentiment expressed in financial news headlines. Sentiment scores associated with each stock symbol are derived to understand the emotional context surrounding stock-related news.
3. Correlation Analysis: Statistical correlations are established between news sentiment scores and stock price movements. Daily stock returns are calculated, and correlation analysis is performed to assess the impact of news sentiment on stock performance.
4.Visualization: Various charts and visualizations are created to better understand the data and analysis results. This includes visualizing the distribution of sentiment scores, publication frequency over time, and trends in publishing times.


## Setup Instructions
1. **Clone the Repository**:
  -echo "# Financial News Analysis" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/juniorworku/financial-news-analysis.git
  git push -u origin main
2. **Set Up Virtual Environment**:
- Create and activate a virtual environment:
  ```
  python3 -m venv venv
  # On Windows: .\venv\Scripts\activate
  # On macOS/Linux: source venv/bin/activate
  ```

## Tools and Technologies
Python
Pandas
NLTK (Natural Language Toolkit)
TextBlob
Matplotlib
TA-Lib (Technical Analysis Library)
PyNance


## CI/CD Setup
The project uses GitHub Actions for CI/CD. The workflow file (`main.yml`) is located in the `.github/workflows/` directory. The workflow runs tests on every push to the main and task-1 branches.

5. **Run the Code**:
- Execute the main scripts or Jupyter notebooks located in the `src/` and `notebooks/` directories.

## Usage
To run the project:

Ensure that Python and the required libraries are installed on your system.
Clone the project repository to your local machine.
Navigate to the project directory.
Run the main script or Jupyter Notebook containing the analysis code.
Follow the instructions provided within the code to perform data analysis, sentiment analysis, and correlation analysis.

