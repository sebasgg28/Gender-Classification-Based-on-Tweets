# Gender-Classification-Based-on-Tweets
Using NLP and Machine Learning to classify people's gender based on their Tweets

### Introduction

More than 5000 tweets were analysed in order to create a model that would classify people tweets based on gender depending on what they say. This model achieved 81% accuracy which is statisfying considering the low amount of data that was available.

### Libraries used:
<br><br>-`Gensim`<br>
-`Spacy`<br>
-`Pandas`<br>
-`Emoji`<br>
-`Sklearn`<br>
-`Pickle` <br>


### NLP Tasks:
1) Removing stop words, punctuation, HTML tags, digits, brackets, etc
2) Normalization

This tasks are necessary to remove any words that don't add meaning such as the or they. So the final outcome would be words that involve topics such as love, cat, video game, etc.

### Machine Learning Algorithms

-RandomForest<br>
-SVC<br>
-A mix of Doc2Vec with SVC

The best model was Doc2Vec with SVC yielded 81% of accuracy.
