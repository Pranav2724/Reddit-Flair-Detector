# Reddit-Flair-Detector

Flow of Code - 

1. The "API Data Extraction.ipynb" file contains the code relevant to the extraction of recent posts from r/Technology Subreddit.
"Technology Sub.csv" is obtained as output of this code

2. The "EDA.ipynb" takes the Technology Sub.csv as input and performs a preliminary Exploratory Data Analysis on it 

3. The "Model Building.ipynb" file then takes the same file as input and performs text cleaning and vectorisation in order to build various
different models to predict the flair.

4. The "WebApp.ipynb" contains the code relevant to the deployment of the ML model and subsequent hosting on heroku

5. The WebApp link contains the link to the heroky hosted WebApp. It takes a link to the r/Technology subreddit post as input and displays the predicted flair
