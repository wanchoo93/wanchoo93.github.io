---
title: "Master's Thesis & Research Assistantship"
collection: teaching
type: "Thesis"
permalink: /teaching/2016-spring-teaching-3
venue: "School of Engineering and Applied Science, University of Pennsylvania"
date: 2021-06-15
location: "Philadelphia, Pennsylvania"
---

My research is being supervised by Dr. [Lyle Ungar](https://www.cis.upenn.edu/~ungar/) Professor in Computer and Information Science at Penn Engineering and Psychology at the School of Arts & Sciences and Dr. [Sharath Chandra Guntuku](https://sharathg.cis.upenn.edu/) Professor in Computer and Information Science. Professor Lyle Ungar’s research group ([World Well-Being Project](https://wwbp.org/)) develops explainable machine learning, deep learning, and natural language processing methods for psychology and medical research. The [World Well-Being Project](https://wwbp.org/) (WWBP) founded by the Father of Positive Psychology, Dr. [Martin EP Seligman](https://ppc.sas.upenn.edu/people/martin-ep-seligman), pioneers scientific techniques for measuring psychological well-being and physical health based on the analysis of language in social media. The World Well-Being Project is based out of the University of Pennsylvania's Positive Psychology Center and Stony Brook University's Human Language Analysis Lab. 

In my ongoing master's thesis I aim to compare the health and lifestyle of people before and after the pandemic hit the world.
This involves studying the impact of public events (Covid-19) on the behavioral, social, and environmental determinants of health with special focus on risks associated 
with cardio-vascular disease (CVD) by leveraging diverse text data (Title of discussion, content of discussion and comments on discussion) 
available on different groups on Reddit (known as Subreddits).

Dual Objective
-----
1. Track and analyze the user engagement across CVD related subreddits (Diet, Physical Activities, Substance Use & Smoking) from January, 2019 to December, 2020
2. Track and analyze how COVID-19 affect language associated with the behavioral, social, and environmental determinants of CVD related health behaviors

Deep Diving in the research objectives
-----
1. **Temporal Shifts:**
    In my research, I seek answer to the question whether social isolation during the pandemic modified any former, trends in eating habits and fitness, frequency and variety of drug abuse, frequency and intensity of physical activities and frequency of smoking and vaping. I wish to uncover these shifts in trends for each broader group by comparing discussions happened in pre-pandemic cluster of subreddits with during pandemic cluster of subreddits. I also assess the influence of discussions happening in one subreddit over other subreddits using temporal topical correlation. 

2. **Drug/Smoking/Alcohol Transition:**
    1. Prospective mortality studies conducted in the 1960s and 1970s showed a clear increase in coronary heart disease mortality with an increase in the number of
cigarettes smoked per day, regardless of the actual number (Doll and Peto 1976, USDHHS 1983).

    2. (Klatsky 1996) concludes alcohol consumption of three or more drinks per day raises blood pressure and levels of triglycerides that are important cardiovascular risk factors.

    3. (Li et al. 2020) concludes that patients with a history of cardiovascular metabolic diseases may face a greater risk of developing into the severe condition upon contraction of Covid-19.

    4. (Leung et al., 2020; Russo et al., 2020; Zhang et al., 2020), provide evidence that vaping or consumption of tobacco increases the risk of infection and progression of Covid-19.

From (i) and (ii) we infer that smoking and alcohol increase the risk of cardio-vascular disease and mortality. From (iii) and (iv) we infer that having a history of cardiovascular disease or consuming tobacco, deteriorates the condition of patient upon contraction of Covid-19 and can be fatal. Thus, it is important to analyze whether the isolation during Covid-19 increased the consumption tobacco, alcohol and illicit substances or were people successful in quitting.

Execution/Procedure
-----
1. Mine the data from over 50 different subreddits that possibly resonate with the 4 broader groups (Diet, Physical Activities, Substance Use & Smoking) using the pushshift API
2. Shortlist the subreddits based on number of posts, comments and members of subreddits
3. Perform exploratory data analysis on the finalized 22 subreddits containing approximately 1 Million posts and 2.7 Million comments
4. Leverage [DLATK](http://dlatk.wwbp.org/index.html) package for Python to identify latent topics present in the posts and comments through Latent Dirichlet Allocation (LDA; Blei et al., 2003)
5. Perform temporal analysis on the topics generated to record inference

Differential Language Analysis ToolKit (DLATK)
-----
[Citation](https://aclanthology.org/D17-2010/)

DLATK is an end to end human text analysis package, specifically suited for social media and social scientific applications. It is written in Python 3 and developed by the [World Well-Being Project (WWBP)](https://wwbp.org/) at the University of Pennsylvania and Stony Brook University. It contains:

1. feature extraction
2. part-of-speech tagging
3. correlation
4. prediction and classification
5. mediation
6. dimensionality reduction and clustering
7. wordcloud visualization

DLATK can utilize:

1. Mallet for creating LDA topics
2. Stanford Parser
3. CMU's TweetNLP
4. pandas dataframe output
