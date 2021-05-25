![BFH Banner](https://trello-attachments.s3.amazonaws.com/542e9c6316504d5797afbfb9/542e9c6316504d5797afbfc1/39dee8d993841943b5723510ce663233/Frame_19.png)
# SaverBot
	SaverBot is a twitter bot that helps people save tweets that they want to.
## Team members
1. Jagannath E Shahi   https://github.com/Jagannathes
2. Mayon Francis       https://github.com/Mayon-Francis
3. Adil Ayanikadan     https://github.com/ASKHIM_LINK
## Team Id
BFH/recj53mi6sGNVB6Dn/2021

## Link to product walkthrough
https://www.loom.com/share/0e18329730a143b199a7d8da917e2660

## How it Works ?
1. It gathers mentions by looking for ```@saverbot1 save```
2. Tries to send DM, If success onto next one
3. Else, It adds it to a pending list, and saves data for a set No. of iterations(120960), which can be modified according to your choice
4. The Tweets to be sent in Pending list are retried automatically
5. Loop continues 

## How to Use ?
- Go to https://twitter.com/saverbot1 and follow the bot, so that it can send you DMs easily.
- When you find any tweet that you like, just reply to the tweet with '@saverbot1 save' and the tweet will be messaged to you  personally in minutes!
- That's it! that's all there is to it, simple, Straight Forward!

## Libraries used
- Tweepy
- pyGithub
- Logging
- Time
- Os
## How to configure
Set up the followinf environment varibles:
- TWITTER_API_KEY
- TWITTER_API_SECRET_KEY
- TWITTER_ACCESS_TOKEN
- TWITTER_ACCESS_TOKEN_SECRET
- GITHUB_TOKEN
- Setup suitable repo and file for saving since ID and modify lines 18 and 19 according to your repository

## How to Run
After making sure u have required modules, just run the python script, it will automatically send the dms and update github repo
