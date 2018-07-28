## Youtube Trending Videos Visualization

### Summary
The goal of this project is to understand trends and gain interesting insights through analyzing the Youtube trending videos for the given period (From Nov'17 to Jun'18). According to Forbes Magzine, YouTube Stars Influence Millennials More Than
Traditional Celebrities. This aroused our interest to see which speciifc videos or which category was the most popular over time. We mainly used Matplotlib and Seaborn packages in Python to generate visualizations related to the video titles and the number of total views. 

We first wanted to know what is the most popular category.

## Bar Plot

#### Insights
We can see the top 2 popular categories are 'Music' and 'Entertainment'. Their views are far more than the other categories. 

Then we analyzed topic popularity using Word Cloud to see what is the top viewed "MUSIC" videos.

## Music WordClouds
#### Insights
We are seeing many pop artist names here. 'Childish' 'Gambino', 'Cardi', 'Ariana', 'Grande', 'Ed Sheeran', 'Jennifer' are the most popular ones among them during this period. More than 95% of the occurrence of the keyword 'america' comes from the MV 'This is America' by 'Childish Gambino'.

We'd like to know how user reacted to the Top 10 Music/Entertainment Videos by analyzing "Dislikes/Likes" Ratios.

## Dislikes/Likes Ratio Graph

![Dislikes/Likes Ratio](relative/path/to/Dislikes:Likes.png?raw=true "Title")

#### Insights
Among the Top 10 viewed music/entertainment videos, YouTube Rewind: The Shape of 2017 has the highest dislikes/likes ratio. This ratio is far more than the other videos'. This finding tells us that sometimes people don't really like the content but were still attracted by it, or maybe the other way around. This is probably because bad/unpleasant things sometimes tend to draw more attentions and be more popular. 


### Datasets
*The dataset is collected using Youtube API. It contains Youtube's daily Trending videos' stats from Nov'17 to Jun'18.*
https://www.kaggle.com/datasnaek/youtube-new

This dataset has 16 features in total. We picked 7 features to explore. 
Trending_date, Title of video, category_id, Number of views, Number of likes, Number of dislikes, Number of comments.

