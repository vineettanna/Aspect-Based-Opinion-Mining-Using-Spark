# Aspect-Based-Opinion-Mining-Using-Spark

### Objective of the Project

You own a restaurant, and you want good reviews, but what really matters? Answering this question that permeates the minds of restaurant owners everywhere, is exactly the goal of this project. **To accomplish this goal, we will use Topic Modeling (Latent Dirichlet Allocation or LDA) and sentiment analysis from Spark MLlib on 4.7M restaurant reviews from 12 metropolitan areas provided by Yelp.com**, to better understand key themes and sentiments that appear in reviews for restaurants across various cuisines.Then through a regression analysis, we aim to derive insights about what dining experience topics carry the most weight when explaining restaurant star rating reviews

### Dependencies

The project in this repository was successfully executed on Python 2.7 and Spark 1.6.

**Libraries Used**: Spark mllib, nltk, texblob

### Flowchart

<img width="815" alt="methodology" src="https://user-images.githubusercontent.com/29344615/33693044-1e1ef026-dab6-11e7-9c95-e0dbd84279b4.png">

- Run Asian LDA.ipynb to get a list of topics and the words belonging to each topic from the customer reviews of the Restaurants belonging to Chinese category
- Using the results from last step we filter reviews containing the words obtained in LDA to find the polarity for each topic (obtained from LDA) at a restaurant level. Then we run Linear Regression to find out which topics (aspects) matter the most for a Chinese restaurant. View Sentiment_Analysis_Linear_Regression.ipynb for this step. 

### Presentation

https://prezi.com/p/wkcbwtuwy3hf/
