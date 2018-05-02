Event Grouping Draft Code


* \[DEVELOPMENT\] 
  * FFNN-BiLSTM-bilinear
    * Baseline classifier-cluster with no context
    * Adapted from Dai & Le (2015) NIPS
  * FFNN-BiLSTM-bilinear + context reader + mutual attention
    * Decked out classifier-cluster
    * Adapted from 
      * BiLSTM classifier: Dai & Le (2015) NIPS
      * CNN reader: Kim (2014) EMNLP
      * Mutual Attention: Hermann et al. (2015) NIPS
  * w/ Role-factored net initialization
    * Decked out classifier-cluster initialized by role-factored embeddings rather than GloVe.
    * Adapted from 
      * BiLSTM classifier: Dai & Le (2015) NIPS
      * CNN reader: Kim (2014) EMNLP
      * Mutual Attention: Hermann et al. (2015) NIPS
      * Role-factored event encoder: Adapted from Weber et al. (2018) AAAI
  * 1 or 2 layered self-attentive reader
    * Adapted from Lin et al. (2017) ICLR
  * Role-factored tensor net
    * Adapted from Weber et al. (2018) AAAI
  * FFNN event-pair pretraining
    * Baseline for Role-factored tensor net (replacing tensors with a simple FFNN).

* \[Our model\]
  * Experimenting with real data (NYT 500k document mixture dataset)
  * Baseline: K-Means/Medoids baselines run on average embeddings
