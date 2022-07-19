# Semantic Similarity using TimeDistributed LSTM

The following notebook, reviews the methodology by which we can build a recurrent neural network that is able to analyze text sentences and determine whether they are congruent in meaning or contradictory in terms of meaning.

The notebook uses the dataset found in this link: https://nlp.stanford.edu/projects/snli/
Available within the kaggle community (https://www.kaggle.com/datasets/stanfordu/stanford-natural-language-inference-corpus), the study focused on two cases: (the first is compatibility in terms of meaning, and the second case is complete difference in terms of meaning).

The adopted methodology relied on the use of TimeDistributed and working on the formulation of the input of the neural network in the form of two sentences, and in each sentence the operations are applied to it inclusively independent of the second sentence, and the aim of this is the ability to extract the characteristics and link the sequence of words for each sentence, and then determine whether the two sentences are identical in terms of meaning Im different.

#Suggested neural network architecture:
![Capture](https://user-images.githubusercontent.com/108609519/179639242-9ffb09a1-f6e3-42da-add0-ba3b1781e870.JPG)

#Result:
![acc](https://user-images.githubusercontent.com/108609519/179639364-b1e8fb95-844b-4e35-b2a0-51dfc19819f6.png)
![loss](https://user-images.githubusercontent.com/108609519/179639410-7eab3c13-90e3-4799-8145-30218ed0e078.png)
