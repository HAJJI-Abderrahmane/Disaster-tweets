# NLP-On-Disaster-tweets
The challenge is to classify if the tweets have some kind of relation to a disaster or not.
I tried three different approaches to solve this problem and they are in seperate notebooks in the repo,
i first started by trying to implement a simple LTSM based model and using glove as my embedding vectors(need to download glove.6B.100d), i hyperparameter tuned it as well with not much of an improvement.
then i tested to preprocess the data then using TFIDF then using standard classification algorithms : MultinomialNB, BernoulliNB, GaussianNB, and logistic Regression.
and finally i used one of bert's variants and it did an amazing job at this classification problem

