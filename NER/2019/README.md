2019
---

### NAACL	
- [**Better Modeling of Incomplete Annotations for Named Entity Recognition**](https://www.aclweb.org/anthology/N19-1079.pdf) [[bib]](https://www.aclweb.org/anthology/N19-1079.bib)  
  *Zhanming Jie; Pengjun Xie; Wei Lu; Ruixue Ding; Linlin Li*
  - Assign epecific labels to words without labels
  - Train a model from (k-1) folds and use it to estimate the label distribution of the imcomplete label sequence
  - Hard: assign probability 1 to a single sequence using constrained Viterbi
  - Soft: calculate the marginal probabilities using a constrained forward-backward procedure
