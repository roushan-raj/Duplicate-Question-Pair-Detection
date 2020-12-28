# Quora-Duplicate-Question-Pair-Detection

Quora is the most popular question-answer platform where users can create and
edit answers and also comment on questions and its answers. The negative side of a
question-answer platform is that Quora has to deal with repeated questions and answers which is a difficult task. To determine duplicate or similar questions, natural
language processing is the most effective method. The cost of miss classification of duplicate questions is very high. Identifying semantically identical questions on, Question
and Answering(Q&A) social media platforms like Quora is exceptionally significant to
ensure that the quality and the quantity of content are presented to users, based on the
intent of the question and thus enriching overall user experience. Detecting Duplicate
questions is a challenging problem because natural language is very expressive, and a
unique intent can be conveyed using different words, phrases, and sentence structuring.
Machine learning and deep learning methods are known to have accomplished superior
results over traditional natural language processing techniques in identifying similar
texts.

In this project, taking Quora for our case study, we explored and applied different
machine learning and deep learning techniques on the task of identifying duplicate
questions on Quora’s question pair dataset. Machine learning models are trained with
features that can help solve this problem. That is why Quora decided to publish the
challenge of classifying duplicate and non-duplicate questions using natural language
processing and machine learning on Kaggle website where they can get many good
solutions for their problem. The task is a binary classification problem where we
need to classify duplicate and non-duplicate questions. To solve this problem various
machine learning models are trained with features that can help solve this problem.

In this repository, some Deep learning models like Convolutional Neural Network (CNN) and Bi-directional Long Short Term Memory (BiLSTM) are developed using GloVe embedding.

- The dataset for this project can be found here: https://www.kaggle.com/c/quora-question-pairs

### First Model is 4 layer Convolutional Neural Network (CNN_4_layer) with GloVe embedding using siamese neural network.

- #### Network Architecture of this model is shown as below:

<img src="Model's%20Flow%20Diagrams/CNN_4_layer.jpg" width="500">


### Second Model is 2 layer Bi-directional Long Short Term Memory (BiLSTM_2_Layer) with GloVe embedding using siamese neural network.

- #### Network Architecture of this model is shown as below:

<img src="Model's%20Flow%20Diagrams/Bi-lstm_2_layer.jpg" width="500">

### Third Model (The best in all 3) is 1 layer Bi-directional Long Short Term Memory (BiLSTM_1_Layer) with a feature "common words between pair of question" with GloVe embedding using siamese neural network.

- #### Network Architecture of this model is shown as below:

<img src="Model's%20Flow%20Diagrams/Bi-lstm%20with%20common%20words.jpg" width="500">
