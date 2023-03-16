# Twitter-Scraping-Project

# Demo:
  Demo video in Linkedin:https://www.linkedin.com/feed/update/urn:li:activity:7041734833370238976/
  
  URL for my twitter scraping app:https://tough-suits-rule-35-233-156-111.loca.lt
  
  google colab link(original file is there):https://colab.research.google.com/drive/1zvxm5Xtt8V73_igRRupl7uhk7FpJ3IH7

# Twitter Scraping 
Scraping the data from the twitter using snscrape library,streamlit framework and mongodb database.scraped data are stored in the mongodb database.
the data can be able to download as a csv file and a json file.to scrape the data we have to use both keyword or hastag..


# Acknowledgement
*Guvi
*Mentor MR.Nethaji nirmal
*Streamlit docs


# Tech Stack
Language:python library(snscrape,pandas),Database:mongodb,GUI Framework:streamlit web

# Scraping the tweets
snscrape python libraray is used to scrape the data from the twitter.the twittersearchsnscraper scrape the data from the twitter without API.this method is passed 
with a query containg the hastag to be search and search data from starting date to ending date

# Uploading data in mongodb
Tweets that are scraped using the snacrape library is inserted into the mongodb database by establishing the client connection.the tweet data are stored under
the twitterstreamlit collection

# Creating the UI
Streamilt app is used for creating the GUI for Twitter scraping.

# Menu 1 : Home
Home menu containg the title and defintion of the app

# Menu 2 :Search
search menu is used to scrape the tweet data using the hastag /keyword for the given data.everytime the search menu deletes the existing data while searching 
the new tweet in order to retrive the tweet information correctly

# Menu 3 : Display
 It scrape the data from the mongodb database are displayed as a dataframe
 
 # menu 4 :Download
  The scraped data from the mongodb database is downloaded as csv file or a json file formats as per requirement..
  # Demo 
  Demo video in Linkedin:https://www.linkedin.com/feed/update/urn:li:activity:7041734833370238976/
  URL for my twitter scraping app:https://tough-suits-rule-35-233-156-111.loca.lt
  google colab link(original file is there):https://colab.research.google.com/drive/1zvxm5Xtt8V73_igRRupl7uhk7FpJ3IH7

  

