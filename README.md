Implementation of a Transformer Encoder model for Kaggle's "CommonLit Readability Prize" challenge. The source data sets can be downloaded from Kaggle's website. The code requires GloVe embeddings and these can be downloaded from https://nlp.stanford.edu/projects/glove/

This code can be used to evaluate the performance of transformer encoder architecture (Vaswani et al., 2017) for a reading comprehension task. Specifically,  the code can be used to evaluate the change in RMSE score owing to a change in the number of input dimensions, number of dimensions in the feed-forward network, and the number of encoder layers. 

An example evaluation is provided below and is based on an architecture that combines the output of a single transformer encoder layer with a FFN with two hidden layers.


References
1. Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. In Advances in neural information processing systems (pp. 5998-6008)
