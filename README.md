# Sentiment-Analysis-for-Marketing
Sentiment analysis is a strategy that uses natural language processing to extract insights from raw  text and comments, for example, to understand the sentiment of a customer/user. In this project, we are trying to enable companies to understand the scope of a product ahead of its launch, also provide insights based on previous customer reviews so marketing teams can better  design their marketing campaigns.

## Understanding the files:
EDA.ipynb : Contains Exploratory Data Analysis, cleaning the data and creating a new data file for the RShiny App, a few basic ML models and their results<br>
Musical_instruments.csv : The dataset for the problem<br>
clean_data.csv : Data obtained after EDA, preprocessing and cleaning<br>


## Problem Statement:
Classification of the emotion behind the customer reviews is a tiresome work for the organizations and analyzing this sentiment helps the organization to  understand customer profiles better.

## Outcomes and Features: 
Creating a sentiment score for each review on a product to generate scope and insights for businesses which can help in understanding the popularity of the product in the market. Creating an RShiny App that companies can use to understand the sentiment behind purchases made on their website.

### Description of problem and details about dataset
Many companies are emerging every day in every industry. Whenever a company launches a new 
product or a line of products, it is important for them to understand the customer’s sentiments 
towards the said products. This will help the companies plan their product and marketing 
strategies. Millions of reviews are generated on the digital medium daily and companies can use 
these reviews and implement various NLP methods on this data to better understand customers’ 
opinions and feedback.
Sentiment Analysis/Opinion Mining is a powerful tool in the field of Natural Language Processing
(NLP) which is growing with new techniques rapidly. It is the process of extracting the sentiment 
behind a given text. It is used to classify the text based on the sentiment into positive, negative, or 
neutral categories. It can be done at a document level, sentence level, or even word level. In the 
current project, we aim to analyze the sentiment behind the reviews at a sentence level. The dataset 
used contains the product data of musical instruments sold on amazon.com. 
The proposed Sentiment analysis tool classifies all these data based on the customer reviews, 
which can be further used by companies to understand the types of products accepted by customers 
and hence can plan their marketing strategies. 
The dataset used in this project is a publicly available dataset collected from amazon.com and 
contains the review data between the years 2009 and 2014. It has 10261 reviews and the following 
9 features. 
1. reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B
2. asin - ID of the product, e.g. 0000013714
3. reviewerName - name of the reviewer
4. helpful - helpfulness rating of the review, e.g. 2/3
5. reviewText - text of the review
6. overall - rating of the product
7. summary - summary of the review
8. unixReviewTime - time of the review (unix time)
9. reviewTime - time of the review (raw)

### Functionalities of the data science tool
The idea behind the functioning of our Data Science tool is to help Companies understand the current industry 
trends, while also helping them understand scope/popularity of a product ahead of its launch, along with insights 
on similar products based on customer reviews which can help marketing team design better ad campaigns. Here 
we are trying to build a Machine learning model using natural language processing where we are trying to 
understand customers’ sentiment from reviews which will help us understand customer satisfaction coefficient, 
this tool Determines the sentiment polarity at sentence level. 
Sentiment extraction or opinion mining manually is a tiring and complicated task for any company especially 
for those with huge market. In our tool we try understanding the data and correlation of features and then compute 
a sentiment score for each order and group them by product to understand product dynamics better, this model 
exponentially decreases the time taken to understand customer’s sentiment.
Deep text analysis is performed on the data to identify most frequently occurring words this is done using 
N-gram analysis or word cloud. These specific words can be used to design Ad campaigns can be designed to 
stress on the improvements made to the product. This model can also help understand which timeframe/season 
the best is to launch a particular product. In this we are also cleaning the data by removing the stop words that 
don’t add any value to the review. Computing the weight of words using TFIDF so that our sentiment score is 
more accurate.


