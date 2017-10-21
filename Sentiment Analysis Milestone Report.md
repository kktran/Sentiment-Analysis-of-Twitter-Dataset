## Problem and Client

This project aims to successfully predict the sentiment (positive or negative) in a large labeled dataset of tweets from the Sentiment140 project (http://help.sentiment140.com/for-students). A project of this nature could provide significant value to clients in industries where communication with customers is important. For example, effective sentiment analysis of customer responses or feedback can identify areas in need of improvement to better the customer experience. Additionally, customers with particularly negative experiences can be targeted, or customer interaction and processing can be automated to reduce the labor needed to serve the client base.

## Dataset and Initial Findings

The dataset originates from the Sentiment140 project with a training set of 1,600,000 tweets automatically based on the presence of positive or negative emojis. The text of the tweet is provided along with the sentiment classification, user, tweet ID, and timestamp. Usernames in tweets (preceded by '@' symbol) were removed prior to analysis, and all columns besides sentiment classification and text were removed. Empty rows were also removed leaving a total of 1,597,281 records. The records are evenly divided between positive and negative sentiment records.
