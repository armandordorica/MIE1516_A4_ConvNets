# MIE1516_A4_ConvNets


### RNN Q1: 
**Directly below this question, answer (a) which architecture worked best and why you hypothesize that is the case**


Naive Bayes with ~82% accuracy for news groups. 
Naive Bayes is efficient in classification because it suffices to detect relevant words to classify a document. For example, soccer, football, basketball are enough words to determine whether a document belongs to the sports category. 
Architectures like RNNs perform better when it comes to sequence to sequence data classification or transformation, which is not required in this case. 


**(b) do the same for the worst performing architecture.**


The words performing architecture is the BRNN with an accuracy of ~20%. This is because bi-directional recurrent neural networks are good to use when a sense of sequence is required, i.e. a sense of dependence on the past for future data, which is not the case in document classification. 


|	Model Name	|	Score	|
|	----	|	---	|
|	Multinomial NB with TF-IDF feature selection	|	0.84	|
|	Logistic Regression	|	0.78	|
|	Pure CNN with pretrained word embedding	|	0.17	|
|	LSTM based RNN with pretrained word embedding	|	0.28	|
|	Bidirectional LSTM RNN	|	0.17	|
|	LSTM based RNN with pretrained word embedding (TBPTT)	|	0.32	|


### RNN.Q2
Run the above architectures for the financial data (note that this data is typically much shorter in length). Try out at least two different architectures (not just optimizer settings, etc.) to see if you can improve the results. 

* **Describe the two architectures you proposed and why you think they might improve results**
* **Answer which architecture worked best (reference a graph) and why you hypothesize this is the case**
* **Do the same for the worst performing architecture**


### Original architectures for Q2: 
* A4_Q2_LSTM_based_RNN_text_classifier_with_pretrained_word_embedding.ipynb 


