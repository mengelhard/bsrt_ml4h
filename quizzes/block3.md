# Applied Data Science, Block 3

---

### Reading Questions

*from [Hirschberg and Manning, 2015](https://science.sciencemag.org/content/349/6245/261)*

1. Which of the following natural language processing (NLP) tasks is *not* discussed by the authors?
  - translating between languages
  - creating new stories and poetry
  - summarizing documents
  - engaging in conversation with a person
  - predicting a writer's (or speaker's) beliefs and emotions
2. Even though "bag of words" models do not interpret words in context, they are nevertheless a difficult baseline to beat for many NLP tasks.
  - True
  - False
3. Much like in image processing, deep learning models for NLP can learn hierarchical representations of text data.
  - True
  - False
4. Natural langauge processing has focused primarily on high-resource languages because:
  - their syntax and vocabulary are better aligned with NLP methodology
  - large training datasets are available in these languages
5. Which of following can be used to help interpret words in context?
  - recurrent neural networks
  - convolutional neural networks
  - models that recognize short phrases in addition to individual words
  - all of the above

*from [Taggart et al., 2018](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2706498)*

6. Which of the following approaches was *not* used by the authors to identify bleeding events?
  - a support vector machine applied to bag of 1-, 2-, and 3-gram features (i.e. based on counts of 1-, 2-, and 3-word phrases)
  - a tree-based classifier applied to bag of 1-, 2-, and 3-gram features
  - a rule-based algorithm
  - a convolutional neural network applied to sequences of word vectors
  - a recurrent neural network applied to sequences of word vectors
7. In term frequency-inverse document frequency weighting, the score for each word in a text sample is (a) directly proportional to the number of times it appears in that sample, and (b) inversely proportional to the number of samples in which it appears.
  - True
  - False
8. Which of the following approaches would be *least* effective for classifying text in which negated references (e.g. *patient denies bleeding*) were important?
  - count individual words, then apply logistic regression to the word counts
  - convert words to vectors, then apply a recurrent neural network to the resulting sequences of word vectors
  - count individual words as well as 2- and 3-word phrases, then apply logistic regression to the word/phrase counts
9. What is the *most likely* explanation for the drop in CNN performance between the training and test sets?
  - the model is not complex enough to capture meaningful patterns in the training data
  - researcher error
  - overfitting
10. When bleeding-absent notes are much more common than bleeding-present notes, the model can perform well by always predicting that bleeding is absent. To counteract this effect, the authors select equal numbers of bleeding-present and bleeding-absent notes during training. Which of the following alternative strategies would *not* achieve a similar effect?
  - penalizing misclassification of bleeding-present notes more heavily by weighting the loss function
  - collecting additional bleeding-present notes until the number of bleeding-present and bleeding-absent notes is equal in the dataset
  - using early stopping to mitigate overfitting to the training set
