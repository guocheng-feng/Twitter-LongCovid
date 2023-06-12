# Twitter-LongCovid
Long COVID generally refers to prolonged symptoms after infection of corona virus, and patient with Long COVID may also experience mental health challenges. Hence, this study aims to understand
better the emotional and mental well-being of individuals with Long COVID, identify the topics that concern them the most, and establish potential correlations between their emotions and social media activities. In terms of our methods, we use pre-trained transformer models for "Long COVID" tweets classification and emotion analysis, and Latent Dirichlet allocation (LDA) for topic extraction. 

For "Long COVID" tweets classification, we apply RoBERTa model to cluster our tweets into following four categories,
- Non-Long COVID Tweets,
- "Long COVID" Tweets without Mental Health Content,
- "Long COVID" Tweets with Implicit Mental Health Statements,
- "Long COVID" Tweets with Explicit Mental Health Statements.

Then, we use DistilRoBERTa transformer model to predict Ekman's six basic emotion within tweets, and LDA algorithm to extract topics within tweets.
