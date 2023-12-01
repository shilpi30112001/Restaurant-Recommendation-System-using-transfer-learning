# Restaurant-Recommendation-System-using-transfer-learning
### Problem Statement
The aim of this project is to develop a robust restaurant recommendation system for different cuisines in a city, leveraging transfer learning to analyze customer reviews on Yelp. The primary objectives include predicting restaurant ratings based on user reviews, providing restaurant recommendations to users using predicted star ratings and sentiment polarity values, and implementing a user-friendly Graphical User Interface (GUI) that takes user inputs to predict the top ten restaurants in a specific city for a given cuisine.

### Objectives
Rating Prediction: Develop a model to predict restaurant ratings using Yelp's dataset and customer reviews.
Recommendation System: Utilize predicted stars and sentiment polarity values to recommend restaurants to users.
Graphical User Interface (GUI): Create an intuitive interface that takes user inputs and predicts the ten best restaurants in a city for a specified cuisine.
Data Description
The dataset employed in this project is sourced from the Yelp Dataset Challenge 2018 (Round 12), comprising various JSON files containing information on businesses, reviews, tips, user details, check-ins, and photos. The dataset is extensive, totaling 6.84 GB, with sub-datasets of varying sizes:

* Business Dataset (139 MB)
* Check-In Dataset (50.3 MB)
* Photo Dataset (34.9 MB)
* Review Dataset (4.39 GB)
* Tips Dataset (203 MB)
* Users Dataset (2.03 GB)
  
The project focuses specifically on the Business and Review datasets. Business objects provide details such as name, location, opening hours, category, average star rating, the number of reviews, and various attributes. Review objects include star ratings, review text, review date, and the number of votes received.

### Model Comparison
The analysis involves the use of the DistilBERT model to calculate sentiment scores. Additionally, a comparison will be made with other models, including LSTM and a random forest classifier, to evaluate and select the most effective approach for the recommendation system.





