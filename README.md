# Zomato-restaurant-clustering

** Project **
*** Project ***


### Introduction 
In today’s digitized modern world, popularity of food apps is increasing due to its functionality to view, book and order for food by a few clicks on the phone for their favorite restaurant or cafes, by surveying the user ratings and reviews of the previously visited customers.Food app like Zomato provides a secular part where user can rate their experience of the visited restaurant or café. Zomato also provides columns for writing classified user reviews. Sharing on the internet is something we usually do. Giving a review is also a useful activity so that other people on the internet can find out something else and see opinions about things. The usual things reviewed by someone in the form of experiences, places, objects, and others. Give a review we usually use text to explain something that we experience with an item, place, or event that we normally experience. Zomato is a site where someone can give a review of a restaurant, how the restaurant is and someone's opinion about the restaurant. Restaurant customer satisfaction can be analyzed by their review on Zomato. Sometimes, restaurants see the reviews in Zomato, but they don't get if the reviews are positive or negative to their restaurants. Reviews on Zomato are still in the form of text and can be classified with positive, negative, or neutral ratings. Zomato doesn’t have an analysis of how users interact with the reviews and what words will indicate whether they like it or not. We need to extract the words in review and analyze it so we can know how users interact in Zomato and get customers' satisfaction by their review. In this paper, we propose a method to analyze user’s sentiment of Zomato Restaurants. We are using Random Forest Classifier to classify the sentiments of users based on their review. We also find words that affect the classifier model. Also, we focus on mining customer reviews, authenticating them and classifying them into positive and negative reviews.

### Problem statement 
- India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. The Project focuses on Customers and Company, we have analysed the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, clustered the zomato restaurants into different segments.

### For Sentiment analysis
- Plotted the distribution of ratings to have an understanding of the proportion of good and bad reviews.
- Made many visualizations which include, top 10/bottom 10 restaurants in terms of average rating.
- The above visualizations are done year wise.
- Had a clear understanding of the cost summary of the restaurants.
- Done pre-processing such as removing emojis, punctuations and only used Adjectives and verbs to reduce dimensionality.
- TF-IDF vectorizer was used to transform the dataset
- Built several models such as Multinomial NB, Logistic regression, Random forest classifier etc.

### For Clustering
- Calculated the time each Restaurant was opened weekly.
- Did the pre-processing, Clubbed some cuisines together so that one-hot encoding would be possible.
- Removed the unwanted variables and Normalized the data.
- Clustered the data using K-means as well as Hierarchical clustering.
