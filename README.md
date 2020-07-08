# MultiphaseNN
Simple feed-forward neural network for classification of multiphase flow regimes

There are a total of 4 script in this repo.

Data_preprocessing deals with the preprocessing of the data, by cleaning it and splitting it into 3 parts (validation, train and test).\

Neural_train is a script just to train the neural network, saving the weights in the NNKLD.pth file.

Testing_NN uses the test dataset to check if the training was successful or not.

Map_test create 2D maps, this is just to validate the results of the network with the current literature.
