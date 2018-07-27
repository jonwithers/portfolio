---
permalink: /turkish-song-nlp/
layout: single
title: Turkish Song NLP
header:
  overlay_color: "#FFF"
  overlay_filter: "0.5"
  overlay_image: /assets/images/turkish_background.jpg
  caption: "Photo by Burak Kebapci from Pexels"
---

## Natural language processing of 14,000+ Turkish songs  
Turkish music is a subject I'm pretty familiar with. This project is an analysis of the lyrics of thousands of Turkish songs. Rather than solving one problem, I decided to answer a couple of related problems using this data:  
- What are the categories of Turkish-language songs that perhaps defy traditional genre labels?  
- Do Turkish songs exhibit thematic changes over time? Do these changes line up with important political or social events?  

### Results
Using Spark, a tool for big datasets, I was able to cluster the songs into two big categories with distinctive vocabularies in each set. I also built a model that could sort the songs into before or after 2004 with better-than-baseline accuracy. For more details, click [here](https://github.com/jonwithers/turkish_song_nlp)
