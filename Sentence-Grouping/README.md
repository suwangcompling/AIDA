Sentence Grouping Draft Code

* Baselines
  * K-Means and HAC directly on sentences as average GloVe embeddings.
  
* SCDV
  * K-Means and HAC directly on sentences as SCDV embeddings.
  * Adapted from Mekala et al. (2017) EMNLP

* Bi-LSTM + HAC
  * Stacked Bi-LSTM classifier + Hierarchical Agglomerative Clustering
  * Adapted from Dai & Le (2015) NIPS
  
* Bi-LSTM + mutual attention + HAC
  * Stacked Bi-LSTM classifier + mutual attention between sentence pairs + Hierarchical Agglomerative Clustering
  * Adapted from Dai & Le (2015) NIPS + Hermann et al. (2015) NIPS

* Bi-LSTM + CNN + HAC
  * Stacked Bi-LSTM classifier + CNN context reader + Hierarchical Agglomerative Clustering
  * Adapted from Dai & Le (2015) NIPS + Kim (2014) EMNLP
  
* Autoencoder+K-means (failed idea)
  * Learning sentence compression and clustering sentence simultaneously
  * Adapted from Yang et al. (2017) ICML
