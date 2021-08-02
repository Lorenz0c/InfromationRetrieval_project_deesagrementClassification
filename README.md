# IR_project_deesagrement_classification

This is the project realized for the Information retrieval course of Università degli studi di Milano.

The project consist in the classification of desagreement responses retrieved by a forum (create_debate dataset) and a chat (MPC dataset) in the seven classes identifyed by Paul Graham.
1000 responses containing desagreement have been manually classified for the first dataset, and 200 for the second one.

The project focuses on different ways of preprocessing the text to classify, paying fewer attention to the classifiers used and their parameters.
The text have been preprocessed through bag of words, word2vec embedding of the responses and word2vec embedding of both the responses and the messages they were directed to.
The classifiers used for the supervised learning are a k-nearest neighbors classifier, a Decision Tree and a Support Vector Machine.

The different combinations of preprocessing and classifiers have been experimented on, and their results evalued.
