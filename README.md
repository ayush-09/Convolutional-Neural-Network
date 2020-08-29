# Convolutional-Neural-Network
In this repository, you seen the deep learning convolutional neural network model using keras/Tensorflow and Natural Language Processing named **Text to Array**.
# Loading The Dataset
  ..* train.csv
  ..* test.csv
# Cleaning The Data
  ..* Beautiful Soup
# NLP
  ..* tokenizer
  ..* Subword text Encoder
# Building The DCNN
  * Convolutional Neural Network
# Compiling The Model
..* The optimizer: the Adam gradient-based optimizer.
..* The loss function. Since I'll using a Softmax output layer, I’ll use the Cross-Entropy loss. Keras distinguishes between binary_crossentropy (2 classes) and categorical_crossentropy (>2 classes).
..* A list of metrics. Since this is a classification problem, we’ll just have Keras report on the accuracy metric.
# Training The Model
1. The training data (inpurts and labels), commonly known as X and Y, respectively.
2. The number of epochs (iterations over the entire dataset) to train for.
3. The validation data (or test data), which is used during training to periodically measure the network’s performance against data it hasn’t seen before.
# Evaluating The Model
Finally evaluate the model to check the accuracy of the model on testing.
