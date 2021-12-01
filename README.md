## PyTorch Implementation of an Encoder-only Transformer

This code implements a Transformer-Encoder model (for a detailed description of an attention-based encoder-decoder architecture refer Vaswani et al., 2017) for Kaggle's "CommonLit Readability Prize" challenge. The source data sets can be downloaded from Kaggle's website. 

This implementation is not the same as fine-tuning BERT because of the following reasons - 
1. it does not estimate the token embeddings and instead uses GloVe embeddings (https://nlp.stanford.edu/projects/glove/)
2. it does not use attention masking

Consequently, this implementation aims to faciliate an understanding of the encoder-based architecture for predictive modelling rather than provide a fine-tuning based applicatin of BERT. Further, the code can be used to explore the change in RMSE owing to a change in the -- 
1. number of input dimensions in an attention layer;
2. number of dimensions in the feed-forward network; or
3. number of encoder layers.

An example evaluation can be viewed by clicking on this link (https://github.com/JayaswalVivek/Transformer_Encoder/wiki/Model-Evaluation)

References
1. Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. 2017. Attention is all you need. In Proceedings of the 31st International Conference on Neural Information Processing Systems (NIPS'17). Curran Associates Inc., Red Hook, NY, USA, 6000–6010.
