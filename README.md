Overview:

This is a simple script to scrape for tweets using the python package called TwitterScraper.

Then the requests retrieves the content.

What You Need:

You would need to download Anaconda Prompt https://www.anaconda.com/distribution/. When you download Anaconda Prompt, it will also download an editor called Spyder. Spyder is an editor where you would write all the code. Then you need to install the package twitter scraper package like this : pip install twitterscraper. You can also follow twitterscraper instructions here https://github.com/taspinar/twitterscraper

What Script Does:

As I said, this is a very simple and small script but it does a lot of work. The script searches a term that you give in and scrapes twitter for information you requested. The results might take some time to load in.

To traverse the data frame for specific values:

When attempting to know the identity of specific fields/columns within your dataframe, you can click on the dataframe object located on your variable explorer window. The above example explores the dataframe, df, which stores information in the form of rows, each row is a tweet, each column is an attribute of a tweet.

You can traverse the contents of the dataframe using two square brackets. For example df[‘username’][4], refers to the username of the 5th tweet, and df[‘text’][0], refers to the text of the 1st tweet in df.

The tweet data frame consists of screen_name, username, user_id, tweet_id, tweet_url, timestamp, timestamp_epochs, text, text_html, links, hashtags, has_media, img_urls, video_url, likes, retweets, replies, is_replied, is_reply_to, parent_tweet_id, reply_to_users

Questions about tweets:
Can we see if retweets have been liked or retweeted? 
Is retweets a number across all users?

Goals:
Focus on data items that have been retweeted more than 0 times.
Separate data frame having tweets that have been retweeted. Get the user_ids to be able.
From user_ids, we need to get the retweet texts
Get user information
Keyword searches: 
“Cyber+Security AND NCCOE”,
 “NCCOE”, 
“SP-1800 or special+publications+1800” (or all variations)
