This is a Email Classifier project based on kaggle ham and spam data.

I implemented

1. Dataset preprocessing for transormation of data to chunks of word for vectorization purpose
2. CountVectorizer and TfIdf Vectorizer for converting textual email to num
3. Did multiple model comparison and stored their accuracy and precision in new dataFrame Bestone(Multinomial Naive Bayes) has precision = 1 and accuracy = 0.97
4. After implementation of every best possible method I stored model for deployment
5. For deployment I'm using Streamlit