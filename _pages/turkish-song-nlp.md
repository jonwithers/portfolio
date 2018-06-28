---
permalink: /turkish-song-nlp/
layout: single
title: Turkish Song NLP
---

## Natural language processing of 14,000+ Turkish songs  
Turkish music is a subject I'm pretty familiar with. This project is an analysis of the lyrics of thousands of Turkish songs. Rather than solving one problem, I decided to answer a couple of related problems using this data:  
- What are the categories of Turkish-language songs that perhaps defy traditional genre labels?  
- Do Turkish songs exhibit thematic changes over time? Do these changes line up with important political or social events?  

### Enter data science  
Each of these questions can be answered using different fundamental techniques in machine learning.  
The first question (what categories are there) is essentially a clustering problem, which needs to be solved using unsupervised learning methods&mdash;we don't know beforehand what categories the songs belong in, and so we can't train a model. Instead, we need to use the data itself to figure out if there is a structure to it.  
The second question (how do Turkish lyrics change over time) can be cast as a classification problem. If we know when a song was created (more on that later), we can train a model to classify the problem into one of two (or more) classes. For instance, if I want to test the hypothesis that Turkish music was influenced by the social changes associated with a particular government regime, I can separate the songs into "before" and "after" classes and train models to try to tell the difference.  

### Data collection  
Data collection for this project was non-trivial. Turkish-language lyrics can be hard to find, and even harder to find with correct metadata. To gather the names of songs, artists, and lyrics, I scraped alternatifim.com, which gathers song lyrics based on user submissions. To gather dates, I queried Spotify's API using the artists and song names and used the first result.
#### Potential problems  
