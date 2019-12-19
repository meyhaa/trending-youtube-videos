# trending-youtube-videos
Data analysis and visualization final project for COGS 108: Data Science in Practice. 

Group Members:
- Meyhaa Buvanesh
- Tian Qiu 
- Allison Patacsil 
- Haoran Sun 

# **Introduction & Background**
According to [the latest traffic report](https://www.similarweb.com/website/youtube.com), YouTube is the world's second largest search engine with 22.77 billion total visits in the last month (28 days). As one of the most popular Art & Entertainment content-providing systems, YouTube spans across cultures and nations, with its trending videos viewed by a wide range of audiences around the globe. Thus, learning about characteristics of trending YouTube videos supports the design and evaluation of personalization services, from precise advertising to recommender systems.

Trending videos on youtube range from anticipated movie trailers to hilarious talk show interviews all the way down to home videos of a young boy yodeling in Walmart.  YouTube has said that Trending aims to showcase videos that are appealing to a wide audience and exhibit what’s happening on YouTube and to a certain extent what’s happening around the world.  This list of trending videos is the same for all users in each country, with an exception in India.  Since Trending isn’t personalized and is the same for all users, it is a great list for YouTube creators to be on as it gives their video more chances of being watched.

For our project, we ask what are the common characteristics in Trending videos? And which of these common factors increase engagement?  We will be measuring engagement as views, ratings, and comments, and we predict that ratings and word choice will important factors in engagment.

# **Data Description**

We will be using a public dataset called "Trending Youtube Video Statistics" built using YouTube's API Services, which is accessible to everyone on [Kaggle](https://www.kaggle.com/datasnaek/youtube-new).  The dataset contains several CSV files with multiple months of data on trending YouTube videos for various countries.  We will be using the "USVideos.csv" file, which includes more than 40,000 observations for trending videos in the United States.  It includes information such as video title, category, publish time, views, etc.
