# Learning ML
This is a collection of tutorials I've followed and mini projects I've worked on while learning ML in PyTorch.

1. PyTorch_basics - coverage of basic concepts in PyTorch, their implementation and usage.
2. NN_MNIST - implementation of a basic neural network trained on the MNIST dataset of digits.
3. CNN_introduction - implementation of a convolutional neural network trained on the CIFAR-10 dataset.
4. Recurrent_Neural_Net (*) - implementation of an RNN for choosing a country for a given name. First done without using the built in rnn module from pytorch and later using it to perform the same task.
5. Transfer_Learning (**) - used an already trained image classification model to fine tune it and comparing the results to training only its last layer.
6. **PROJECT_Image_Captioning** (unfinished) - combined a fine-tuned CNN with a custom made LSTM for image captioning.
7. **Autoregression_Emojis** - implementation of the PixelCNN model and trained on emojis to geenerate new ones.

(*) - Download the folder "rnn_data" and upload it to your google drive in the folder at location "My Drive/google_colab", or change the path in the code.

(**) - Download the "hymenoptera_data" dataset [here](https://download.pytorch.org/tutorial/hymenoptera_data.zip) and upload it to your google drive in the folder at location "My Drive/google_colab" or change the path in the code.
