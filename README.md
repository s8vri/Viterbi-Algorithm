# Viterbi Algorithm

In this assignment the Viterbi Algorithm was implemented for finding the optimal state (here: tag) sequence given the sequence of observations (words). Based on this a bigram POS tagger based on HMMs was implemented.

The parameters (*initial, transition, and emission probabilities*) were learned from data and a maximum 
likelihood training procedure for supervised learning of HMMs was implemented.

The trained model was evaluated on the unseen data from the test set. The Viterbi Algorithm was run on each of the models and the output is a tagged corpus in the two-column CoNLL format (dd-test.txt). A brief discussion of the findings is found in the *discussion.pdf* file, the accuracy scores and a visualization of the performance
of the Viterbi algorithm are found in the two *png* files accordingly.
