# DTAUC - Unsupervised Decision Trees for Axis Unimodal Clustering

The use of decision trees for obtaining and representing clustering solutions is advantageous, due to their interpretability property. We propose a method called Decision Trees for Axis Unimodal Clustering (DTAUC), which constructs unsupervised binary decision trees for clustering by exploiting the concept of unimodality. Unimodality is a key property indicating the grouping behavior of data around a single density mode. Our approach is based on the notion of an axis unimodal cluster: a cluster where all features are unimodal, i.e., the set of values of each feature is unimodal as decided by a unimodality test. The proposed method follows the typical top-down splitting paradigm for building axis-aligned decision trees and aims to partition the initial dataset into axis unimodal clusters by applying thresholding on multimodal features. To determine the decision rule at each node, we propose a criterion that combines unimodality and separation. The method automatically terminates when all clusters are axis unimodal. Unlike typical decision tree methods, DTAUC does not require user-defined hyperparameters, such as maximum tree depth or the minimum number of points per leaf, except for the significance level of the unimodality test. Comparative experimental results on various synthetic and real datasets indicate the effectiveness of our method.

## Reference

```bibtex
@Article{info15110704,
AUTHOR = {Chasani, Paraskevi and Likas, Aristidis},
TITLE = {Unsupervised Decision Trees for Axis Unimodal Clustering},
JOURNAL = {Information},
VOLUME = {15},
YEAR = {2024},
NUMBER = {11},
ARTICLE-NUMBER = {704},
URL = {https://www.mdpi.com/2078-2489/15/11/704},
ISSN = {2078-2489}
}
