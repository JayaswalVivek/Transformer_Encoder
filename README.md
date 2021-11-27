Implementation of a Transformer Encoder model for Kaggle's "CommonLit Readability Prize" challenge. The source data sets can be downloaded from Kaggle's website. The code requires GloVe embeddings and these can be downloaded from https://nlp.stanford.edu/projects/glove/

This code can be used to evaluate the performance of transformer encoder architecture (Vaswani et al., 2017) for a reading comprehension task. Specifically,  the code can be used to evaluate the change in RMSE score owing to a change in the number of input dimensions, number of dimensions in the feed-forward network, and the number of encoder layers. 

Click on this link to view the change in model's performance (in terms of RMSE value) owing to a change in the model's hyperparameters (https://github.com/JayaswalVivek/Transformer_Encoder/wiki/Model-Evaluation)

References
1. Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. "Attention is all you need." In Advances in neural information processing systems, pp. 5998-6008. 2017.
