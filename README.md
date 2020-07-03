# Tweet-Analyzer
Twitter sentiment analysis allows you to keep track of what’s being said about your product or service on social media, and can help you detect angry customers or negative mentions before they turn into a major crisis.

At the same time, Twitter sentiment analysis can provide interesting insights.
## DS with Reddy

Web App Link : https://twitter-sentimental-analysiss.herokuapp.com/

This is a cool web app integrated with twitter which takes the twitter handel as as input and does :

1.Analyze the tweets of your favourite Personalities

This tool performs the following tasks :
1. Fetches the 5 most recent tweets from the given twitter handel
2. Generates a Word Cloud
3. Performs Sentiment Analysis a displays it in form of a Bar Graph

2.This tool fetches the last 100 tweets from the twitter handel & Performs the following tasks
Converts it into a DataFrame

Cleans the text
1. Analyzes Subjectivity of tweets and adds an additional column for it
2. Analyzes Polarity of tweets and adds an additional column for it
3. Analyzes Sentiments of tweets and adds an additional column for it


This respository contains all the files for end to end model building and deployment of tweet analyzer web app

Procfile : To generate command to run the app

Tweet_Analyzer.ipynb : Model building File

Twitter Data : File created after every query on the web app

Requirements.txt: Requirement file

setup.sh : predefined file for streamlite on heroku

This app is created on a tool called Streamlit which saves you from the headache of front-end devlopment ,you can install it by:
Streamlit documentation: https://docs.streamlit.io/en/latest/

pip install streamlit

& to run it on local host : streamlit run myfile.py
