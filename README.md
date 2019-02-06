# Analyzing the tweet archive of Twitter user @dog_rates
#### a simple project of scrapping @WeRateDogs twitter account and wrangling data

## Project Overview

The dataset that I wrangled (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

My tasks in this project were as follows:
	
	Data wrangling, which consists of: 
		Gathering data
		Assessing data
		Cleaning data
	Storing, analyzing, and visualizing your wrangled data
	Reporting on 1) data wrangling efforts and 2) data analyses and visualizations

All steps in order preparing dataset describe in a pdf file named: wrangle_report, but as summary, for gathering data, I used 'Requests' library and 'tweepy' API and rest of cleaning and visualization had done in jupyter notebook.

## Summary of Findings

For every successful twitter account, number of “likes” and “retweet” are vital measures. WeRateDogs has started 2015 and at the late 2015, both "likes" and "retweet" were similar together but after that time "retweet" counts has increased very smoothly and even can say at Jan 2017 reaches to a relatively steady situation, meanwhile “like” counts after Nov 2016 was a skyrocket date to increase sharply and continue this trend. So, hardworking, keep frequently posting and be diligent is the most important secret for social network business model to reach to exponential growth in followers. On other hand the difference between these two measures can be notice from active social media followers perspective, the followers who have active twitter accounts and prefer to share interesting tweets with their followers, and the rest of followers who are less professional users of twitters and just make “like” some tweets.

Tweets during time from 6 a.m. to 1 p.m. have biggest chance for more like and retweet.

Puppo is the most favorite of customized various stages of dogs (stages: doggo, pupper, puppo, and floof(er))

Bedlington Terrier and Afghan Hound breeds, respectively, have most like and retweet.

A report of findings can be find in a pdf file named: act_report.
