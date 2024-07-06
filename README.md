# Intel Product Sentiment Analysis

This project performs sentiment analysis on Intel products using various data scraping, preprocessing, and machine learning techniques.

## Project Overview

The primary goal of this notebook is to analyze customer reviews and sentiments about Intel products. It includes the following steps:
1. **Data Collection**: Web scraping reviews using Selenium.
2. **Data Preprocessing**: Cleaning and preparing the text data for analysis.
3. **Sentiment Analysis**: Using TextBlob to analyze the sentiment of the reviews.
4. **Machine Learning Models**: Applying models such as Random Forest and KMeans for sentiment classification.
5. **Visualization**: Generating word clouds and other visual representations of the data.

## Notebook Contents

The notebook is organized into sections that follow the project's workflow:
1. **Introduction**: Brief introduction to the project.
2. **Web Scraping**: Using Selenium to scrape review data from websites.
3. **Data Preprocessing**: Cleaning and preparing the data, including handling missing values, text cleaning, and language detection.
4. **Sentiment Analysis**: Applying TextBlob for sentiment scoring.
5. **Feature Extraction**: Using TF-IDF for feature extraction from text.
6. **Model Training**: Training machine learning models to classify sentiments.
7. **Evaluation and Visualization**: Evaluating model performance and visualizing results using word clouds and other plots.

Additionally, you need to have:

Python 3.12 or later.
ChromeDriver installed for Selenium to work correctly.

To run this notebook, you need to install the following libraries:

```bash
pip install numpy
pip install pandas
pip install selenium
pip install webdriver_manager
pip install textblob
pip install wordcloud
pip install emoji
pip install langid
pip install matplotlib
pip install scikit-learn 




