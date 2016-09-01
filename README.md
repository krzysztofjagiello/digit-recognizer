# Digit Recognizer
This is an implementation of a convolutional neural network for recognizing hand written digits using the MNIST dataset. A validation accuracy of about 99.3% is obtained after training for 11 epochs. 

Here is an example of an output generated by display_random.py.

<img src="https://github.com/Shobhit117/digit-recognizer/blob/master/figure_1.png" height=300px width=400px>

## Requirements

* Python 2.7
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [h5py](http://www.h5py.org/)
* numpy
* matplotlib
* pandas

## Dataset

* The model is trained on the MNIST dataset downloaded from [Kaggle](https://www.kaggle.com/c/digit-recognizer). 

* The file train.csv contains the labels and pixel intensity values for 42000 images. The pixel intensity values are integers between 0 and 255 which are converted to float by dividing by 255.0 during preprocessing.

* test.csv contains pixel intensity values for 28000 images.

* The predictions for each image in test.csv are written in predictions.csv for submission at Kaggle.

## Model

<img src="https://github.com/Shobhit117/digit-recognizer/blob/master/model.png">

## Training and Testing

* To train the model execute `train.py` using `python train.py`.
* The file `test.py` predicts outputs to the test set and writes them in predictions.csv. To run, use `python test.py`.
* `display_random.py` takes 25 random images from the test set and displays their predictions.

## Using the model architecture and weights for other applications

The model architecture and weights are saved in files `model_architecture.json` and `model_weights.h5` respectively for future use. Loading the model and weights is explained in the [Keras documentation](https://keras.io/getting-started/faq/#how-can-i-save-a-keras-model).



