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
  * 1 or 2 layered self-attentive reader.
    * Adapted from Lin et al. (2017) ICLR
  * Role-factored tensor net.
    * Adapted from Weber et al. (2018) AAAI
