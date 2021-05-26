# Analysing-the-Andriod-app-market

A comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play



## Project:

Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention. 

##  Dataset:

Let's take a look at the data, which consists of two files:

* `apps.csv`: contains all the details of the applications on Google Play. There are 13 features that describe a given app.
* `user_reviews.csv`: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.


## Tools used:

Code: Python Version: 3.7

For data wrangling and visualization: Pandas, plotly, seaborn, matplotlib 

## Reports 

With more than 1 billion active users in 190 countries around the world, Google Play continues to be an important distribution platform to build a global audience. For businesses to get their apps in front of users, it's important to make them more quickly and easily discoverable on Google Play. To improve the overall search experience, Google has introduced the concept of grouping apps into categories.

This brings us to the following questions:

* Which category has the highest share of (active) apps in the market?
* Is any specific category dominating the market?
* Which categories have the fewest number of apps?

![Alt Text](https://github.com/aayanmaity/Analysing-the-andriod-app-market/blob/main/images/Plot%201.png)

We will see that there are 33 unique app categories present in our dataset. Family and Game apps have the highest market prevalence. Interestingly, Tools, Business and Medical apps are also at the top.


After having witnessed the market share for each category of apps, let's see how all these apps perform on an average. App ratings (on a scale of 1 to 5) impact the discoverability, conversion of apps as well as the company's overall brand image. Ratings are a key performance indicator of an app.

![Alt Text](https://github.com/aayanmaity/Analysing-the-andriod-app-market/blob/main/images/Plot%202.png)

From our research, we found that the average volume of ratings across all app categories is 4.17. The histogram plot is skewed to the left indicating that the majority of the apps are highly rated with only a few exceptions in the low-rated apps.


Let's now examine app size and app price. For size, if the mobile app is too large, it may be difficult and/or expensive for users to download. Lengthy download times could turn users off before they even experience your mobile app. Plus, each user's device has a finite amount of disk space. For price, some users expect their apps to be free or inexpensive. These problems compound if the developing world is part of your target market; especially due to internet speeds, earning power and exchange rates.

How can we effectively come up with strategies to size and price our app?

* Does the size of an app affect its rating?
* Do users really care about system-heavy apps or do they prefer light-weighted apps?
* Does the price of an app affect its rating?
* Do users always prefer free apps over paid apps?

![Alt Text](https://github.com/aayanmaity/Analysing-the-andriod-app-market/blob/main/images/Plot%203.png)

![Alt Text](https://github.com/aayanmaity/Analysing-the-andriod-app-market/blob/main/images/Plot%204.png)


We find that the majority of top rated apps (rating over 4) range from 2 MB to 20 MB. We also find that the vast majority of apps price themselves under $10.

So now comes the hard part. How are companies and developers supposed to make ends meet? What monetization strategies can companies use to maximize profit? The costs of apps are largely based on features, complexity, and platform.

There are many factors to consider when selecting the right pricing strategy for your mobile app. It is important to consider the willingness of your customer to pay for your app. A wrong price could break the deal before the download even happens. Potential customers could be turned off by what they perceive to be a shocking cost, or they might delete an app they’ve downloaded after receiving too many ads or simply not getting their money's worth.

![Alt Text](https://github.com/aayanmaity/Analysing-the-andriod-app-market/blob/main/images/Plot%205.png)

Different categories demand different price ranges. Some apps that are simple and used daily, like the calculator app, should probably be kept free. However, it would make sense to charge for a highly-specialized medical app that diagnoses diabetic patients. Below, we see that Medical and Family apps are the most expensive. Some medical apps extend even up to $80! All game apps are reasonably priced below $20.
