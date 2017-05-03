2013
---

### ACL
- [**Co-regularizing character-based and word-based models for semi-supervised Chinese word segmentation**](http://www.aclweb.org/anthology/P/P13/P13-2031.pdf) [[bib]](http://www.aclweb.org/anthology/P/P13/P13-2031.bib)  
  *Xiaodong Zeng; Derek F. Wong; Lidia S. Chao; Isabel Trancoso*
  - Multi-view learning by co-regularizing character-based and word-based models
  - Use the segmentation agreements as constrains to bias the training of the two models
  - A log-linear interpolation combination for decoding

- [**Graph-based Semi-Supervised Model for Joint Chinese Word Segmentation and Part-of-Speech Tagging**](http://www.aclweb.org/anthology/P/P13/P13-1076.pdf) [[bib]](http://www.aclweb.org/anthology/P/P13/P13-1076.bib)  
  *Xiaodong Zeng; Derek F. Wong; Lidia S. Chao; Isabel Trancoso*
  - Graph construction
    - A symmetric k-NN graph whose edge weights are measured by a similarity function (co-occurrence statistics)
  - Label propagation

### EMNLP
- [**Deep Learning for Chinese Word Segmentation and POS Tagging**](http://www.aclweb.org/anthology/D/D13/D13-1061.pdf) [[bib]](http://www.aclweb.org/anthology/D/D13/D13-1061.bib)  
  *Xiaoqing Zheng; Hanyang Chen; Tianyu Xu*
  - First neural network architecture for CWS
    - Input window, Lookup table, Neural network, Tag inference
  - Tagging score
