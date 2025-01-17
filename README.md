# DeepRepo_MinRNN

Normally, all you have to do is run one by one all the cell, and the two graph available in this github should be computed.

The test has been made with the dataset "sarcasm.json" provided in this Github.

The conception of minGRU and minLSTM is taken from the following article : 
https://arxiv.org/abs/2410.01201
Therefore, the implementation of a few functions is described in detail in this article, with the global theory about this two models.

Here are the different models implemented : 
- Pytorch GRU
- HomeMade GRU
- minGRU
- minGRU with Parallel scan
- Pytorch LSTM
- HomeMade LSTM
- minLSTM
- minLSTM with Parallel scan
