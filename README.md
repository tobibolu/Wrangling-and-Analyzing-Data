# Wrangling-and-Analyzing-Data
Using Python and it's libraries to gather data from a variety of sources and formats. Assessing their quality and tidiness then cleaning them
The dataset wrangled was the We Rate Dogs twitter archive. We Rate dogs is a twitter account known for rating people's dogs with a humorous comment about the dog.

# Key Tasks
I stored the twitter archive which was in a csv format into a Pandas Dataframe. I then downloaded a tsv file of image predictions from Udacity's servers using the Requests library. The image predictions were developed using a neural network to determine what breed of dog was present in each tweet.I then queried the Twitter API for each tweets JSON using Python's Tweepy library and stored each entire set of JSON data in a txt file which was then read line by line into a Pandas Dataframe.
After all the Data was gathered I assessed them both visually and programatically for quality and tidiness issues and used Pythons libraries to clean each issue found
