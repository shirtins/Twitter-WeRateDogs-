# Making Sense of the twitter archive data
This majorly shows the skill of data wrangling as a data analyst.

Analysis is done a dataset gotten from twitter.

This is a project i did while undergoing the Udacity Data Analyst Nanodegree
the dataset that I wrangled (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates),also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs).

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because ["they're good dogs Brent."](https://knowyourmeme.com/memes/theyre-good-dogs-brent) WeRateDogs has over 4 million followers and has received international media coverage.
The following tasks are done: 
- Step 1: Gathering data

- Step 2: Assessing data

- Step 3: Cleaning data

- Step 4: Storing data

- Step 5: Analyzing, and visualizing data

- Step 6: Reporting

It involved the use of 3 datasets:
- Twitter archive dataset: Contains the basic tweet data.
- Additional Data via the Twitter API: Contains retweet and favourite count, etc..
- Image Predictions File: classification of breeds.

This project involved gathering different kind of data; csv, tsv,json using twitter api (Tweepy)

Thing to note: When using the data gotten via tweeter, i created my twitter developers account to get the access to the tweets,
thus my API Keys, Secrets, and Tokens are not included.

The twitter archive data containing about 2000 dog tweets (cleaned data) that contain dog pictures and their rating by #WeDogRates.
WeDogRates
The csv file was handled using python and its extended libraries
When starting to analyze the data i had initial assumptions to begin with:
- Dogs rating majorly depended on the kind of picture posted
- There are some certain dog type that have higher rating than others
- Tweets with a lot of retweets and favourites usually get a higher rating.
All these were assumped with the understanding of #WeRateDogs rating system which could be read here,
[Rating System](https://knowyourmeme.com/memes/theyre-good-dogs-brent)
All charts were created using python libraries: `seaborn` and `matplotlib`,

**All thanks to Udacity/ALX for the learning.**
