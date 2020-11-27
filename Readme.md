# Can Twitter be Chill ? - Chilling Effects in Social Media 


## 1. Abstract
The original paper focuses on wikipedia data, where people are mostly passive. They look for information but do not interact with each other. But does a chilling effect also exist on platforms with interaction ? To look into this question, we will collect tweets (from Twitter) over the period of study of the article. Tweets with the keywords of the 48 topic keywords from the article will be analysed, giving us insight on the chilling effect upon active behavior of people. We will investigate these keywords from the original article, to distinguish between "meta" tweets, talking about the effect of surveillance, or discussing an entirely different subject, for example keyword nuclear, or attack might be related to different topics entirely, whereas ammonium nitrate or dirty bomb might not be so often present in tweets about non privacy sensitive subjects. We will have information about retweets, likes, users posting the content, and will therefore expand or restrict the original paper focus. 

## 2. Research Questions
Does the chilling effect also take place on social media ?
Is social media a usable medium to ask these kinds of questions ?

## 3. Proposed dataset
Using the python library Twint (https://github.com/twintproject/twint) we will scrape twitter data from around our period. Existing datasets cannot be freely shared as per twitter privacy policy.
After a few tests, we were quickly able to collect thousands of tweets, for example the "dirty bomb" keyword got 18 000 tweets over a two year period.


## 4. Methods
We will need to perform some pre-processing of the data to account for deleted or banned user accounts, and also perform other necessary steps to get as close as possible to a natural experiment.
Then we will perform a segmented regression analysis like in the original paper to detect changes in trend when it comes to tweeting about terrorism-related subjects.
Then we will report the findings, answering the questions asked in 2.


## 5. Proposed timeline

1. Week 1: Collecting Tweets and Data Wrangling
2. Week 2: Data Modelling and Analysis and Visulisation
3. Week 3: Wrap-up and Create Data Story

We have worked on the collection of data already, as it was a crucial point to test the feasibility. But we will need to fully finish it.

## 6. Organisation Within the Team :
* Collecting the original data
  * Dividing the collection among the team members
  * Merging the collected data into one raw dataset

* Creating a natural experiment dataset
  * Accounting for the retroactive dataset aspect : what about users that were deleted/banned or shadow-banned (yes, this does exist !) ?
  * Accounting for the public/private aspect : what bias does the data have because of us
* Creating a reference dataset
  * Performing regression analysis on the dataset
  * Aggregate the data using a pertinent time granularity
* Performing the regression analysis
* Conclusions



## 7. Questions for TAs (?)
1. We have missing data because of deleted or shadow-banned accounts how to handle that
2. We notice some tweets that are irrelevant to the subject, they speak of non-privacy-related issues, how to handle that?
