# MIND_Article_Recommender

The MIcrosoft News Dataset (MIND) is a large-scale dataset for news recommendation research. It was collected from anonymized behavior logs of Microsoft News website. The mission of MIND is to serve as a benchmark dataset for news recommendation and facilitate the research in news recommendation and recommender systems area. Link: https://msnews.github.io/

MIND contains about 160k English news articles and more than 15 million impression logs generated by 1 million users. Every news article contains rich textual content including title, abstract, body, category and entities. Each impression log contains the click events, non-clicked events and historical news click behaviors of this user before this impression. To protect user privacy, each user was de-linked from the production system when securely hashed into an anonymized ID.

This code is designed to use Natural Language Processing (NLP) to identify a list of similar articles based on a sample article title submitted by the user.

Data Source: https://www.kaggle.com/arashnic/mind-news-dataset
