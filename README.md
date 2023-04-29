# UNB-GCN
We proposed a univariate neurodegeneration biomarker (UNB) based GCN semi-supervised classification framework. 
We generated UNB by comparing the similarity of individual morphological atrophy pattern and the atrophy 
pattern of Aβ + AD group according to the brain morphological abnormalities induced by AD. For the GCN 
semi-supervised classification model, we took the UNBs of individuals as the features of nodes and 
constructed the weight of edges according to the similarity of phenotypic information between individuals, 
which explored the essential features of individuals through spectral graph convolution. The attention 
module was constructed and embedded into the GCN framework, which may refine the input morphological 
features to highlight the main impact of AD on the cerebral cortex and weaken the instability caused 
by individual diversities, thereby identifying the significant ROIs affected by AD and improving the 
classification accuracy.

## Requirements

The code is tested on Ubuntu 16.04 with PyTorch 0.4.1/1.0.0 and Python 3.6.


## References

[1] [Thomas N. Kipf, Max Welling, Semi-Supervised Classification with Graph Convolutional Networks, ICLR 2017](https://arxiv.org/abs/1609.02907)
