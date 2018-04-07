# Wearable Sensor based Human Activity Recognition with Recurrent Neural Networks
## Abstract

This work is concerned with HAR based on wearable sensors, which record acceleration, gyroscope and sometimes magnetic field data. Traditional HAR approaches often require domain specific knowledge to generate handcrafted features, a feature selection strategy to identify the most informative ones and a supervised learning algorithm to solve the task. This thesis evaluates the practicability of RNNs for the HAR problem. RNN based models are well suited in theory, since they extract informative features from raw sensor data, can be trained in a supervised fashion and are tailored to model temporal dynamics. The investigated architectures are based on LSTMs and GRUs, a hybrid network with convolutional and recurrent layers and a residual network applied on recurrent layers. The performance of the networks was evaluated on three public and a single private dataset, covering a diverse selection of activities and subjects. All datasets were subject to a train, validation and test split and a LOSOCV evaluation procedure. In order to have a valid comparison with the traditional HAR approach, a RF classifier was trained on time and frequency domain features. Furthermore, a grid search was carried out for all models, based on a validation set, to find the best hyperparameters. Results indicate that the proposed networks outperform the traditional approach in both evaluation procedures on three out of four datasets and are competitive in the remaining one. This suggests that the time extensive process of generating handcrafted features based on domain specific knowledge can be avoided by relying on RNNs. However, any NN based model requires careful hyperparameter optimization, which in turn is a very time consuming process with an uncertain prospect of success.
