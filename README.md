## PyTorch Implementation of an Encoder-only Transformer

This code implements a Transformer-Encoder model (for a detailed description of an encoder-decoder transformer architecture refer Vaswani et al., 2017) for Kaggle's "CommonLit Readability Prize" challenge and the source data sets can be downloaded from Kaggle's website. While BERT (Devlin et al., 2018) is also a Transformer-Encoder model, this implementation is not the same as fine-tuning BERT because --
1. it does not estimate the token embeddings and instead uses GloVe embeddings (https://nlp.stanford.edu/projects/glove/);
2. it does not make use of masking (or another form of self-supervised learning) during the training process; and
3. it makes the use of position-based encoding optional.

Consequently, the current implementation aims to facilitate an understanding of the encoder-based architecture for predictive modelling. It can be used to explore the change in RMSE owing to -- 
1. an inclusion/exclusion of position-based encoding; or
2. a change in the number of (a) input dimensions in an attention layer; (b) attention heads; (c) dimensions in the feedforward network; or (d) encoder layers. 

An example evaluation can be viewed by clicking on this link (https://github.com/JayaswalVivek/Transformer_Encoder/wiki/Model-Evaluation)

*References*
1. Devlin, Jacob, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint arXiv:1810.04805. 2018.

2. Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. "Attention is all you need." In Advances in neural information processing systems, pp. 5998-6008. 2017.
