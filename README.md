# Twitter Sentimental Analyzer

{Created By: Ishaan Takkar, under the guidance of Dr. Parshant Singh Rana (Associate Professor, TIET Patiala) }

Live Link of Project - https://share.streamlit.io/takkar99/twitter-sentimental-analyzer/main/app.py

Twitter Sentimental Analyzer can analyze the tweets of your favorite Personalities and perform the sentimental analysis on last 100 tweets for the person.

Two Functions can be Performed: Tweet Analyzer, Generate Twitter Data.


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


This respository contains all the files for end to end model building and deployment of tweet analyzer app.

Procfile : To generate command to run the app

Tweet_Analyzer.ipynb : Model building File

Twitter Data : File created after every query.

Requirements.txt: Requirement file

setup.sh : predefined file for streamlite.

This app is created on a tool called Streamlit which saves you from the headache of front-end devlopment ,you can install it by:
Streamlit documentation: https://docs.streamlit.io/en/latest/

This app can be run on your local directly if you use the following commands on commandline:

(a). pip install streamlit

(b). streamlit run myfile.py

Following Screen will be displayed on the browser:
![image](https://user-images.githubusercontent.com/63262408/134002810-734e7d61-f90d-4176-b233-28bb60859f9a.png)

Type the exact twitter username of person you want to search:
![image](https://user-images.githubusercontent.com/63262408/134002969-bceeb7d0-e0ca-439a-a365-942c5989ba7c.png)

Tool 1: Analyze the tweets of your favourite Personalities

For the first Activity i.e. Show Recent Tweets ,it will give output as recent 5 tweets of the person.
![image](https://user-images.githubusercontent.com/63262408/134003250-469a3e90-a16c-4479-ac8c-8e5ed4594ee8.png)

For the second activity i.e. to generate word Cloud , it will give the output as wordcloud of recent 5 tweets.
![image](https://user-images.githubusercontent.com/63262408/134003403-2d94e4b4-9941-4015-9fd6-c4efbb23da37.png)

For the second activity i.e. to visualise the Sentimental Analysis.
![image](https://user-images.githubusercontent.com/63262408/134003513-f63e3d0b-b6d2-4aa4-8f7e-6c0f2e620cc7.png)

Tool 2: Fetches the last 100 tweets from the twitter handel & Performs the following tasks
Converts it into a DataFrame

![image](https://user-images.githubusercontent.com/63262408/134003916-28c579c9-9e77-43b7-bae2-ff09260dfe4d.png)

This data will automatically store in the Twitter_Data file and will updates whenever you run the app for another person.
