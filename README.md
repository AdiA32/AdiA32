# Aditya Agrawal
 - UCSD Data Science and Cognitive Science with Machine Learning and Neural Computation
 - Open for full time positions and internships


**Click on the links below to view the repository of the project**

# [S&P 500 STOCK RECOMMENDATION PROJECT (Work In Progress)](https://github.com/AdiA32/SP500-ML-Project)
### *(ML,LSTM,NLP,DEEP LEARNING, FINANCIAL MODELLING, VISUALIZATION)*
### [Poster](#stocks-poster)
<!-- **(WIP)** This is an ongoing project as part of the UCSD *Data Science Student Society(DS3) Projects Committee 2023*. This project began with a dataset of historical S&P 500 data and an original goal of building a stock recommendation system - i.e using AI and ML models to predict the Opening Price movement of a given stock. Given this background, we approached this challenge in 2 ways:

* **Financial Modelling** - Predicted Opening Stock Price of Google Stocks (GOOGL)  using- Random Forests, LSTMs, Koopman Neural Networks, all implemented in Python with TensorFlow and scikit-learn packages.
* **Scraping Twitter** -  We used the Twitter API to perform Sentiment Analysis on tweets that referenced a given stock and tried to build a system to analyse whether the Twitter sentiment has an effect on the opening Price of the stock.  -->
## Project Introduction
This project aims to optimize stock portfolio allocation utilizing a blend of LSTM models, sentiment analysis, and portfolio optimization techniques. LSTM models forecast stock movements, while sentiment analysis gleans insights from Twitter and news data. Recommendations from these techniques are optimized through an Efficient Frontier model to maximize return for a given risk level.

## LSTM Models
We selected LSTM for its capability to capture long-term dependencies and handle non-stationarity in stock prices. However, it does not account for the Random Walk Hypothesis. The LSTM model demonstrated reasonable accuracy in predicting Google's opening price movements, albeit with an average overprediction of $3.04 per day.

## Sentiment Analysis
Sentiment analysis uses data from Twitter and news outlets processed by two NLP models, VADER and BERT. VADER is simple and resource-efficient but struggles with complex sentences, whereas BERT excels at understanding sentence context but requires substantial resources. Sentiments are aggregated from Twitter and news sources using a weighted approach.

## Portfolio Optimization
The Efficient Markets Problem is circumvented using Modern Portfolio Theory, focusing on Return and Risk rather than predicting price. The Efficient Frontier is graphed, providing a visual representation of the optimal portfolio combinations for the highest expected return for a given risk level or vice versa.

## Future Direction
Future steps encompass enhancing sentiment analysis, exploring other deep learning models like CNNs or transformer models for stock predictions, investigating advanced portfolio optimization methods, developing a real-time portfolio recommendation tool, improving model interpretability, and establishing performance metrics via backtesting.


# [FAKE AMAZON REVIEWS PROJECT](https://github.com/sukikrishna/FARS)
### *(ML, DECISION TREES, RANDOM FOREST CLASSIFIERS,LINEAR ALGEBRA, NLP, N-Grams Classification)*




# [FAKE AMAZON REVIEWS PROJECT](https://github.com/sukikrishna/FARS)
### *(ML, DECISION TREES, RANDOM FOREST CLASSIFIERS,LINEAR ALGEBRA, NLP, N-Grams Classification)*
The project revolves around the development of a model to predict the validity of mock Amazon product reviews. By utilizing n-grams, random forest machine learning models, sentiment analysis, and other tools, the goal is to create an accurate and reliable solution. Data from Amazon's extensive database of product reviews serves as the foundation for this project.

N-grams are employed to extract features from the text data, capturing contextual relationships between words. These sequences of n words enable the identification of patterns and linguistic nuances, which play a crucial role in determining the validity and sentiment of the reviews.

Random forest classifiers are utilized to classify the reviews effectively. This ensemble learning method combines multiple decision trees, resulting in robust predictions. By utilizing the extracted n-grams as input features, the random forest model learns from labeled data, where the validity of reviews is known, and can subsequently predict the validity of new, unseen reviews.

Additionally, sentiment analysis techniques are applied to analyze the sentiment expressed in the reviews. This enables the model to determine the emotions and polarity associated with the text, further enhancing the prediction accuracy.

Throughout the project, various tools and techniques such as preprocessing, feature engineering, and model optimization are employed. Steps like tokenization, stop word removal, and stemming are applied to clean and standardize the text data. Feature engineering techniques such as TF-IDF assign weights to the n-grams based on their relevance. Cross-validation and hyperparameter tuning ensure optimal performance of the random forest models.

The resulting model aims to provide a robust and efficient solution for predicting the validity of mock Amazon product reviews. Such a tool has the potential to automate the review classification process, enhance quality control, and improve the overall credibility of product reviews on Amazon's platform.

# [Project Mentality](https://github.com/AdiA32/Mentality)
### *(Python, Automation, Mobile-Integration, Web scrapping)*
The "Project Mentality" is an automated program designed to deliver daily curated quotes from famous thinkers to the user's phone via SMS. Its main purpose is to provide motivation and inspiration for personal improvement on a daily basis.

The program employs web scraping techniques to gather quotes from various online sources such as websites, blogs, and social media platforms. The scraped data undergoes analysis and data cleaning processes to ensure the accuracy and relevance of the quotes, eliminating any errors or inconsistencies.

Using Python, the program is automated to deploy daily and send the curated quotes directly to the user's phone as SMS messages. This automation is achieved by integrating APIs or third-party services that enable sending SMS messages from a Python script. By integrating with SMS gateway providers, the program ensures seamless delivery of the curated quotes, providing a convenient and accessible user experience.

Furthermore, the project involves learning advanced techniques for automated web deployment. This includes setting up a reliable hosting environment using containerization technologies like Docker and leveraging cloud platforms such as AWS or Google Cloud for efficient scaling and management.

In summary, the "Project Mentality" is an automated program that delivers daily curated quotes to the user's phone via SMS. Through web scraping, data cleaning, and mobile integration, it aims to motivate users and inspire personal growth. The project also emphasizes learning advanced techniques for automated web deployment to ensure smooth operation and scalability.

# [Python BlackJack Simulation](https://github.com/AdiA32/Project-Blackjack)
In this project, I implement a Python simulation of a Blackjack game using object-oriented programming techniques. Blackjack is a card game typically played at casinos where each player competes against the dealer to get a score closest to 21, without going over 21. At the start of the game, each player and the dealer are given 2 cards. A person's set of cards is referred to as their hand. The player's own cards (their hand) are visible to themselves and only one of the dealer's cards is visible to everyone. After everyone receives their cards, the dealer asks each player whether they would like to hit (take another card) or stand (keep their current cards). Each player can hit (take a card) as many times as they would like to get their score as close to 21 as possible, without going over. Afterwards, the dealer reveals their card and decides to hit or stand. Lastly, the final scores are calculated and the winner is announced




### Stocks Poster
<img src="stocks v2.png"
     alt="Poster Presentation found at https://github.com/AdiA32/SP500-ML-Project/blob/8108dc4d7da7ba720e47e155f334ca02ccc29a0d/stocks%20v2.pdf"/>