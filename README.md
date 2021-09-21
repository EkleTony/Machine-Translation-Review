# Machine-Translation-Review
In this notebook, we shall   build a deep neural network that functions as part of an end-to-end machine translation pipeline. And compare their various accuracy

# Machine Translation Project
## English to French
* RNN Recurrent Neural Networks (or more precisely LSTM/GRU) have been found to be very effective in solving complex sequence related problems given a large amount of data. They have real time applications in speech recognition, Natural Language Processing (NLP) problems, time series forecasting, etc. 

* Sequence to Sequence (often abbreviated to seq2seq) models are a special class of Recurrent Neural Network architectures typically used (but not restricted) to solve complex Language related problems like Machine Translation, Question Answering, creating Chat-bots, Text Summarization, etc.


## Introduction
In this notebook, we shall   build a deep neural network that functions as part of an end-to-end machine translation pipeline. Our completed pipeline will accept English text as input and return the French translation.

- **Preprocess** - We'll convert text to sequence of integers.
- **Models** Create models which accepts a sequence of integers as input and returns a probability distribution over possible translations. After learning about the basic types of neural networks that are often used for machine translation.
- **Accuracy of eeach model** We shall check and compare the accuracy of models

### Dataset used
Download and unzip mar-eng.zip file from http://www.manythings.org/anki/
