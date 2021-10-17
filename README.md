# NeuralLanguageModelForTheRepublicUsingGloVeEmbeddingsAndLSTM

Data Cleaning

### Train language model

We can now train a statistical language model from the prepared data. The model we will train is a neural language model. It has a few unique characteristics:

 It uses a distributed representation for words so that different words with similar meanings
will have a similar representation.

 It learns the representation at the same time as learning the model.

 It learns to predict the probability for the next word using the context of the last 100 words.

Specifically, we will use an Embedding Layer to learn the representation of words, and a
Long Short-Term Memory (LSTM) recurrent neural network to learn to predict words based on
their context. Let’s start by loading our training data.
