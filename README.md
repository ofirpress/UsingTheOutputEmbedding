This is the code for the EACL '17 paper ["Using the Output Embedding to Improve Language Models" by Ofir Press and Lior Wolf](http://aclweb.org/anthology/E/E17/E17-2025.pdf).

The folder BayesianRNN implements the weight tying method (with and without weight decay) over the code of [Yarin Gal's BayesianRNN](https://github.com/yaringal/BayesianRNN/tree/master/LM_code) language model (commit 7b923cc84f48f2dc65113aa012c3b99dfa6abed8 ). 
Notice that the number of units in each LSTM layer was changed to 1500. 

The folder ptb_word_lm implements the weight tying method and projection regularization on the language model from the official [tensorflow tutorials](https://www.tensorflow.org/versions/r0.8/tutorials/recurrent/index.html#language-modeling) . 
(The full original code is available [here](https://github.com/tensorflow/tensorflow/tree/r0.8/tensorflow/models/rnn/ptb) ). 

For an implementation of **weight tying** and **three way weight tying** in **neural machine translation models**, see [Nematus](https://github.com/rsennrich/nematus). (For decoder weight tying use the flag "--tie_decoder_embeddings", and for three way weight tying also use "--tie_encoder_decoder_embeddings").

If you use these methods in your research, please cite our paper:
```
@InProceedings{press2017using,
  author    = {Press, Ofir  and  Wolf, Lior},
  title     = {Using the Output Embedding to Improve Language Models},
  booktitle = {Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics: Volume 2, Short Papers},
  month     = {April},
  year      = {2017},
  address   = {Valencia, Spain},
  publisher = {Association for Computational Linguistics},
  pages     = {157--163},
}
```

