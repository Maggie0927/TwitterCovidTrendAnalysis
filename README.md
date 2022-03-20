# TwitterCovidTrendAnalysis
Individual Final Project for the course *Big Data Platform*

## Data Source ##
A collection of Twitter data that is stored in Google Cloud Storage

## Objective ##
Identify whether Twitter can be considered a credible source of information, which reflects the risk of contracting a COVID infection.

## Approach ##
Conduct data analysis using PySpark

## Steps ##
1. Discard irrelevant tweets
2. Complete thorough EDA to identify which variables can be used to profile the Twitterers
3. Identify the most prolific / influential Twitterers
- By message volume (original content)
- By message retweet (how often their messages are being retweeted)
- Identify these Twitterers (government entities / health organizations / news outlets / social media influencers / someone else)
- Visualize the distribution of tweet / retweet volume by Twitterers and types of organizations
4. Find where these Twitterers located
- Identify the relationship between the pandemic progression and locations of these Twitterers
- Visualize the geographical distribution
5. Perform timelines analysis of these tweets
- Find any significant peaks and valleys
- Find any data collection gaps
6. Analyze uniqueness of the messages
- Use Jaccard similarity / Simhash to measure uniqueness / similarity
- Visualize message duplication for each group of Twitterers (government entities / health organizations / news outlets / social media influencers / other)
