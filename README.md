![head](https://miro.medium.com/max/1280/1*L69bb4OirTPvwRvkDLVFng.png)

# LSTM-RNN



# Emedding layer:


## " Word embeddings can be thought of as an alternate to one-hot encoding along with dimensionality reduction. "



If we use one-hot encoding on words in textual data, we will have a dummy feature for each word, which means 10,000 features for a vocabulary of 10,000 words. This is not a feasible embedding approach as it demands large storage space for the word vectors and reduces model efficiency.

Embedding layer enables us to convert each word into a fixed length vector of defined size. The resultant vector is a dense one with having real values instead of just 0’s and 1’s. The fixed length of word vectors helps us to represent words in a better way along with reduced dimensions.

# Conclusion
Embeddings are a great way to deal with NLP problems because of two reasons. First it helps in dimensionality reduction over one-hot encoding as we can control the number of features. Second it is capable of understanding the context of a word so that similar words have similar embeddings. 


# LSTM-RNN:
LSTM networks are an extension of recurrent neural networks (RNNs) mainly introduced to handle situations where RNNs fail. 
