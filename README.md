This is the code for the paper ["Using the Output Embedding to Improve Language Models" by Ofir Press and Lior Wolf](http://arxiv.org/abs/1608.05859).

The folder BayesianRNN implements the weight tying method over the code of [Yarin Gal's BayesianRNN](https://github.com/yaringal/BayesianRNN/tree/master/LM_code) language model (commit 7b923cc84f48f2dc65113aa012c3b99dfa6abed8 ). 
Notice that the number of units in each LSTM layer was changed to 1500. 

The folder ptb_word_lm implements the weight tying method and projection regularization on the language model from the official [tensorflow tutorials](https://www.tensorflow.org/versions/r0.8/tutorials/recurrent/index.html#language-modeling) . 
(The full original code is available [here](https://github.com/tensorflow/tensorflow/tree/r0.8/tensorflow/models/rnn/ptb) ). 
