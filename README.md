# MIE1516_A4_ConvNets


### RNN Q1: 
**Directly below this question, answer (a) which architecture worked best and why you hypothesize that is the case**
Naive Bayes with ~82% accuracy for news groups. 
Naive Bayes is efficient in classification because it suffices to detect relevant words to classify a document. For example, soccer, football, basketball are enough words to determine whether a document belongs to the sports category. 
Architectures like RNNs perform better when it comes to sequence to sequence data classification or transformation, which is not required in this case. 


**(b) do the same for the worst performing architecture.**
The words performing architecture is the BRNN with an accuracy of ~20%. This is because bi-directional recurrent neural networks are good to use when a sense of sequence is required, i.e. a sense of dependence on the past for future data, which is not the case in document classification. 
