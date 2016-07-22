# digit-recognizer
We train a convolutional neural network to recognize hand written digits using the MNIST data set and the Keras library. The model is trained with batches of 50 images for 11 epochs. A validation accuracy of about **99.3%** is obtained. 

* **train.py** trains the CNN for 1 epoch and saves the model and weights.
* **test.py** predicts the outputs for the test set and saves the results in **predictions.csv**.
* **display_random.py** randomly selects 25 images from the test set and displays them with their predicted outputs.

Here is an example of an output generated by **display_random.py**.

<img src="https://github.com/Shobhit117/digit-recognizer/blob/master/figure_1.png">
