# Hacker_news_posts

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted
stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is
extremely popular in technology and startup circles, and posts that make it to the top of the
Hacker News listings can get hundreds of thousands of visitors as a result.

## Data
The source data for this study can be found here (https://www.kaggle.com/hacker-news/hackernews-posts). It contains almost 300,000 rows, each row representing a post. The data is of 2016. However, for this study we make use of a version that been reduced to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. This file was prepared by Dataquest and can be downloaded from here (https://app.dataquest.io/m/356/guided-project%3A-exploringhacker-news-posts/1/introduction).

Let us start with reading in the data, and displaying the header row and a small sample.
+ id: the unique identifier from Hacker News for the post
+ title: the title of the post
+ url: the URL that the posts links to, if the post has a URL
+ num_points: the number of points the post acquired, calculated as - - the total number of
+ upvotes minus the total number of downvotes
+ num_comments: the number of comments on the post
+ author: the username of the person who submitted the post
+ created_at: the date and time of the post's submission

### We are gonna answer two main questions below:
+ Do Ask HN or Show HN receive more comments on average?
+ Do posts created at a certain time receive more comments on average?
