# YouTube_Trending_Videos_Project

## Scenario
YouTube has millions of videos competing for viewers' attention. This analysis explores trending videos from November 14, 2017 to June 14, 2018 across the US, UK, France, and Canada, with data recorded by the hour each video remained trending. It helps content creators understand what factors drive a video to trend, suchs category, publish timing, and engagement metrics. so they can make more informed decisions about their own content strategy.


## Executive Summary
- The analysis included 161,251 trending-video records from YouTube across the United States, Great Britain, France, and Canada, covering the period from November 14, 2017 to June 14, 2018, which represents approximately seven months of data. The dataset was cleaned, and category_id was mapped to readable category names using category_name. The time_frame column was converted into a numeric format and its fixed by one hour for all treading vidoes, and a day_to_trend column was created. Exploratory data analysis (EDA) was then conducted using bar charts, a correlation heatmap, scatter plots, a time series, and word clouds. The project focused on data exploration and visualization, with no predictive models included.

Key findings:
- Categories: Entertainment was the most frequently trending category, with approximately 42K records, followed by Music with around 28K records. Other frequently appearing categories included People & Blogs, Comedy, and News & Politics.
- Day of week: Friday had the highest number of trending records, with approximately 28K records, while the weekend had fewer records. Saturday had the lowest number, with around 16K records.
- Countries: The four countries had relatively similar numbers of trending records, ranging from approximately 39K to 41K. However, Great Britain recorded the highest total number of views, with approximately 228B views, despite having the fewest records.
- Engagement: Views and likes showed a strong positive correlation of 0.79. Likes and comment count also had a strong correlation of 0.78, while dislikes and comment count had a correlation of 0.73. Music had the highest average number of likes, while Nonprofits & Activism had the highest average number of dislikes relative to its likes.
- Time on trending: Most videos remained on the trending list for only one day. The number of videos decreased steadily as the number of days on the trending list increased.
- Channels and content: Several of the top trending channels were late-night talk shows, including The Late Show with Stephen Colbert, Late Night with Seth Meyers, TheEllenShow, The Tonight Show, and Jimmy Kimmel Live. Other frequently appearing channels included WWE, CNN, ESPN, and Netflix. Common words and phrases found in titles and tags included "donald trump", "talk show", "music video", "punjabi song", and "Real Madrid"

Conclusions and recommendations:
Overall, the results indicate that trending content was concentrated in specific categories, particularly Entertainment and Music, while many of the top trending channels were established channels with a large audience. Most videos also remained on the trending list for a short period, with one day being the most common duration. Based on these findings, content creators may consider focusing on high-volume categories such as Entertainment and Music and publishing during weekdays, particularly around Friday. Understanding differences between country audiences may also help in creating more targeted content. It is important to note that each record represents a video appearing on the trending list on a specific day. Therefore, the same video can appear multiple times in the dataset, meaning that the record counts represent trending appearances rather than unique videos.



## File Directory/table of contents
= 



  
