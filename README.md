# Twitter-LongCovid
Long COVID refers to persistent symptoms and possible mental health challenges experienced by patients after a COVID-19 infection. Hence, this study aims to understand
better the emotional and mental well-being of individuals with Long COVID, identify the topics that concern them the most, and establish potential correlations between their emotions and social media activities. 

In terms of our methods, we use pre-trained transformer models for "Long COVID" tweets classification and emotion analysis, and Latent Dirichlet allocation (LDA) for topic extraction. 

For "Long COVID" tweets classification, we apply RoBERTa model to cluster our tweets into following four categories,
- Non-Long COVID Tweets,
- "Long COVID" Tweets without Mental Health Content,
- "Long COVID" Tweets with Implicit Mental Health Statements,
- "Long COVID" Tweets with Explicit Mental Health Statements.

Then, we use DistilRoBERTa transformer model to predict Ekman's six basic emotion within tweets, and LDA algorithm to extract topics within tweets.

### Files and Folders:
- ***tweets_classification.ipynb***: codes using RoBERTa model to classify tweets into the four categories.
- ***tweets_emotion.ipynb***: codes using DistilRoBERTa model to classify tweets into the Ekman's six basic emotions.
- ***tweets_LDA.ipynb***: codes using LDA algorithm to cluster tweets into the pre-defined number of groups depending on whether they shares the same topic.
- ***tweets_visualization.ipynb***: codes visulzing previous tweets classification and emotion analysis results.
- ***data/***: training data that we manually labeled for tweet content classification.
