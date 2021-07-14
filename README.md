# xgimi_CFA
XGIMI projector customer feedback analysis (amazon reviews)

# Task one: Building a semantic index to perform searches on customer reviews

* Extract data from amazon
* Basic text preprocessing and savaing into right file format (list of clean sentences in .txt file)
* Download from tensorflow website and load [nnlm-en-dim128](https://tfhub.dev/google/nnlm-en-dim128/2) module. Token based text embedding trained on English Google News 200B corpus. The module takes a batch of sentences in a 1-D tensor of strings as input. This module is based on the work of Yoshua Bengio, Réjean Ducharme, Pascal Vincent, Christian Jauvin. [A Neural Probabilistic Language Model](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf). Journal of Machine Learning Research, 3:1137-1155, 2003.
* Set up dynamic random normal matrix for dimensionality reduction.
* Build index
* Apply index


Adopted from: https://www.tensorflow.org/hub/tutorials/tf2_semantic_approximate_nearest_neighbors


# To Do:
## Task 2: build a fulltext index and compare results, merge if necessary.
## Task 3: include implentation of Neo4j-based sentiment search from previous project to improve expressiveness of search
