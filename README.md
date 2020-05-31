# Piano Composer

In this project we generate Piano Music using LSTM networks. midi files that contain music notes are used for training

## Requirements

* Python 3.x
* Packages:
	* Music21
	* Keras
	* Tensorflow
	* h5py



The network will use every midi file in ./midi_songs to train the network. The midi files should only contain a single instrument to get the most out of the training.

**NOTE**: You can stop the process at any point in time and the weights from the latest completed epoch will be available for text generation purposes.




