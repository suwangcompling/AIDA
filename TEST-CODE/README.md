Various tests along the way.

* Sentence autoencoder (toy-test)
  * IN: randomly generated sentence; OUT: decoded same sentence.
  * NOTE: Bahdanau et al. (2015) attention.
* Sentence classifier (toy-test)
  * IN: randomly generated sentence pairs (either with the same vocab or different, 1/0 labeling); OUT: binary labels.
  * NOTE1: CNN text classifier modified from Kim (2014).
  * NOTE2: Bi-LSTM text classifier modified from Dai & Le (2015).
* Sentence classifier (doc-mix-mock)
  * IN: randomly generated document mixtures; OUT: hierarchical clusterings.
  * NOTE1: document mixture context are read with CNN as per Kim (2014).
  * NOTE2: mutual attention mechanism modified from Hermann et al. (2015).
