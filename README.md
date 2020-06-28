# Twitter Media Sentiment Analysis (BLACK LIVES MATTER)
This project is meant to identify and quantify the bias in media representation if there is any. I collected the tweets from the thirty most followed news media bodies on twitter containing a list of words surrounding a political issue for analysis. The code is reusable but this analysis has been done on the Black lives matter movement.
## Data Streaming and Collection:
+ The twitter API tweepy allows us to stream the data as well as filter it but the restriction is that it can only be upto 7 days older, this study was done on tweets from 21st June 2020 till 28th June 2020, yet the code is compatible with more than the standard twitter developer account. 
+ The data collected here is that of the tweets from the top thirty news media twitter platforms, the list of these channels has been attached to another markdown. 
+ The Twitter API access is permitted through a twitter developer account after which we get a API access credentials which I saved in a different notebook and accessed it using the Pickle python serialization.
+ I stored all the tweets by these news handles in the last seven days containing the words, ["Black+lives+matter","racism", "police+brutality", "george+floyd","breonna+taylor","ahmaud+arbery", "police+protest","defund+police","minnesota+police"]
+ This was done in three sessions so as to avoid running out of API calls in the standard (free) twitter developer account. 
+ About 1163 tweets were stored as well as the number of retweets for each of the tweets. 
