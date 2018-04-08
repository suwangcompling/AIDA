Various tests along the way.

* Sentence autoencoder (toy-test)
  * IN: randomly generated sentence; OUT: decoded same sentence.
  * NOTE1: Bahdanau et al. (2015) attention.
* Sentence classifier (toy-test)
  * IN: randomly generated sentence pairs (either with the same vocab or different, 1/0 labeling); OUT: binary labels.
  * NOTE1: CNN text classifier modified from Kim (2014).
* Sentence classifier (doc-mix-mock)
  * IN: randomly generated document mixtures; OUT: hierarchical clusterings.
  * NOTE1: mutual attention mechanism modified from Hermann et al. (2015).
