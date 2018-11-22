# NLP_Machine_Translation
NLP Machine Translation application which translates from English to French.
In this project, we will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Our completed pipeline will accept English text as input and return the French translation.

We'll convert text to sequence of integers, then build severl neural network models including basic RNN (GRU), word embedding+RNN, Bi-directional RNN, encoder-decoder RNN (LSTM) with attention mechanism, then construct a final model. Our final model consists of word embedding and bi-directional RNN which outperforms all previous models and achieve very high training and validation accuracy.

Besides our final model, embedding+RNN and encoder-decoder RNN with attention mechanism also achieve high training and validation accuracy.
