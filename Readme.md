Both Twitter usernames (handles) are checked to make sure they're valid.
A call to the Twitter API retrieves the first 200 tweets from your Twitter feed (excluding any retweets).
A call to the Twitter API retrieves the first 200 tweets from the celebrity's Twitter feed (excluding any retweets).
Your 200 tweets are sent as a single body of text to the Watson Personality Insights (PI) API to be analyzed.
The celebrity's 200 tweets are sent as a single body of text to the Watson Personality Insights (PI) API to be analyzed.
The Watson PI API runs a sorting & matching algorithm to find the most common attributes between both bodies of text.
The application prints the results to the user.