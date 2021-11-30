Implementation of a Transformer-Encoder model (refer Vaswani et al., 2017 for an attention-based encoder-decoder architecture) for Kaggle's "CommonLit Readability Prize" challenge. The source data sets can be downloaded from Kaggle's website. The code requires GloVe embeddings and these can be downloaded from https://nlp.stanford.edu/projects/glove/

This code can be used to evaluate a change in RMSE owing to a change in the -- 
1. number of input dimensions for the attention layer;
2. number of dimensions in the feed-forward network; or
3. number of encoder layers.

An example evaluation can be viewed by clicking on this link (https://github.com/JayaswalVivek/Transformer_Encoder/wiki/Model-Evaluation)

References
1. Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. "Attention is all you need." In Advances in neural information processing systems, pp. 5998-6008. 2017.
