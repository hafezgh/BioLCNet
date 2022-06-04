You only need to run the “main” notebook after uploading the other files to the colab local directory to reproduce the MNIST results corresponding to the best model.

Please first run the first cell to install the most recent stable version of BindsNet.

As stated in the paper, BioLCNet was trained in a layerwise fashion, so we have also put the file of the pre-trained weights of the local connection, and it is automatically loaded when running the second cell of the notebook. The whole training (10000 MNIST training samples) on colab GPU should take about 9 hours. Afterwards, you could also run the next cell for testing on the whole MNIST test set (The time required is 256*2 since the agent does not have a learning phase).
