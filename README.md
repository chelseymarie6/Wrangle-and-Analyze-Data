# Wrangle-and-Analyze-Data
Udacity's Data Analyst Nanodegree - Project 4

Real-world data rarely comes clean. Using Python and its libraries, the project gathers data from a variety of sources and in a variety of formats, assesses its quality and tidiness, then provides a cleaned version. This process is known as data wrangling. These wrangling efforts are documents in a Jupyter Notebook and a separate write-up. 

The dataset which will be wrangled  is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. 

###Software Needed
- Need to be able to work in a Jupyter Notebook on your computer.

- The following packages (libraries) need to be installed:
pandas
NumPy
requests
tweepy
json

###Enhanced Twitter Archive

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, tweets with ratings only have beenfiltered for  (there are 2356).

###Additional Data via the Twitter API

Back to the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered from Twitter's API. Well, "anyone" who has access to data for the 3000 most recent tweets, at least. The project queries Twitter's API to gather this valuable data.
