# Exploratory Data Analysis on Play Store App Reviews

## 1. Abstract:
Mobile Applications are an integral part of our daily lives. As they are easy to create and are lucrative, it becomes essential to do comprehensive analysis of play store app data and understand the demand of users.
Through our exploratory data analysis, we tried our level best to bring out some important insights from the data to devise strategies for growth and retention

## 2.	Introduction:
### We are provided with two datasets:
* Play_store_data: It contains the basic details of the app like number of user reviews, ratings, etc.
* User_reviews: It contains the user reviews and its sentiment score for the respective app.
We need to explore and analyze the data to discover key factors responsible for app engagement and success. 
### The contents of play_store_data are:
* App: It contains the name of the app with a short description (optional).
* Category: This section gives the category to which an app belongs. In this dataset, the apps are divided among 33 categories.
* Size: The disk space required to install the respective app.
* Rating: The average rating given by the users for the respective app. It can be in between 1 and 5.
* Reviews: The number of users that have dropped a review for the respective app.
* Installs: The approximate number of times the respective app was installed.
* Type: It states whether an app is free to use or paid.
* Price: It gives the price payable to install the app. For free type apps, the price is zero.
* Content rating: It states which age group is suitable to consume the content of the respective app.
* Genres: It gives the genre(s) to which the respective app belongs.
* Last updated: It gives the day in which the latest update for the respective app was released.
* Current Ver: It gives the current version of the respective app.
* Android Ver: It gives the android version of the respective app.

### The contents of user_reviews are:
* App: It contains the name of the app with a short description (optional).
* Translated_Review: It contains the English translation of the review dropped by the user of the app.
* Sentiment: It gives the attitude/emotion of the writer. It can be ‘Positive’, ‘Negative’, or ‘Neutral’.
* Sentiment_Polarity: It gives the polarity of the review. Its range is [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’.
* Sentiment_Subjectivity: This value gives how close a reviewer’s opinion is to the opinion of the general public. Its range is [0,1]. Higher the subjectivity, closer is the reviewer’s opinion to the opinion of the general public, and lower subjectivity indicates the review is more of a factual information.
## 3.	Challenges Faced:
*	Reading the dataset and comprehending the problem statement.
*	Examining the business KPIs for app development and devising a solution to the problem.
*	Handling the error, duplicate and NaN values in the dataset.
*	Designing multiple visualizations to summarize the information in the dataset and successfully communicate the results and trends to the reader.

## 4.	Conclusion:
The marketplace is crowded with all types of mobile apps as it has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market.
Today, even businesses who never would’ve needed apps in the past are getting into the game to meet customer demand for an app that makes their lives easier or to stay ahead of the tech curve.
Thus, through this exhaustive analysis of approx. 10k apps we discovered following key factors responsible for app engagement and success in recent study:
1.	We found that among 33 unique app categories present in our dataset, apps related to Games and Medical have the highest market prevalence                according to their ratings, though the number of apps are more for family and tools as well.
2.	But, the number of installs is higher for Communication, Social and productivity genres whereas Tools, Entertainment, Education related genres have maximum number of apps among all 119 genres.
3.	It was interesting to note that
o	Users have paid more for lite and high rating apps.
o	Users have installed more apps of the ones having high reviews
o	Installs of app doesn't depends on Size.
4.	From the sentiment analysis we found users showed more positive sentiments for paid apps and were harsh while showing sentiments for free apps. Also, Neutral sentiments were less for paid ones i.e users were true to reviews once they have paid for it.
5.	Users gave maximum reviews for game category followed by family. Also, the positive and negative sentiments were highest for games category.


### Different Python libraries used to complete this EDA:
*	Pandas
*	NumPy
*	Matplotlib.Pyplot
*	Seaborn
*	Wordcloud

## References:
*	GeeksforGeeks
*	Analytics Vidhya
*	Stackoverflow
*	Python libraries documentation
*	Data camp
