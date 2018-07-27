---
permalink: /reddit-nlp/
layout: single
title: Reddit NLP
header:
  overlay_color: "#FFF"
  overlay_filter: "0.5"
  overlay_image: /assets/images/reddit_background_cropped2.jpg
  caption: "Photo by rawpixel.com from Pexels"
---

## Classifying Reddit posts by subreddit
Reddit is a social media platform with a large user base and organized online communities. r/BlackPeopleTwitter and r/WhitePeopleTwitter are two such communities that are both relatively popular and contain similar content. In both of these communities, or subreddits, users post screenshots of individual tweets from Twitter and other users comment on them. This project takes the post title and top comment from thousands of posts and classifier them according to the language that they use.  
### Results
<![alt text](https://jonwithers.github.io/portfolio/assets/images/randomforest.png)
I built a Random Forest classifier that was able to classify test data with an accuracy score of 78.6%. The model also revealed interesting insights about what differentiates these two online spaces. To find out more about what makes r/WhitePeopleTwitter and r/BlackPeopleTwitter different, click [here](https://github.com/jonwithers/reddit-scraping)!
