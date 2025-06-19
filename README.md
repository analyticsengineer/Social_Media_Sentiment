
![o61rbtks](https://github.com/user-attachments/assets/e0b8dfeb-fb70-4542-b58a-2e2b00d6e897)

#### Social Media sentiment
Hi everyone, I resumed publishing on my blogs my career growth. I literally took a year break, but I am fully ready to focus on my career.
I decided to start learning my Data Analysis skills. I chose to start with data cleaning exercises using Python and SQL.
I found it had to get a case study online, so I used a ChatGPT prompt to help me generate a data cleaning exercise and case study.

Here is the prompt I used

`I need case study with datasets for data cleaning like 10 make it social media, sales, marketing and business inclined
Here is one of the case study outputs generated`

**Social Media Sentiment Posts**
- Dataset: 50 000 tweets about your brand
- Columns: tweet_id, user_handle, timestamp, text, likes, retweets, sentiment_score
- Cleaning objectives:
- Parse timestamp into datetime; handle inconsistent time zones
- Remove bot or spam accounts (e.g. duplicate user_handle with >100 tweets/day)
- Strip URLs/mentions from text; normalize emojis
- Impute missing sentiment_score with mean

I also asked ChatGPT to provide me with the appropriate data for the data cleaning exercise

`You can download the csv file from this respository`

I cleaned the data in Google Collaboratory using libraries Pandas, regrex, emoji

`You can download the Python Notebook file from this respository`
