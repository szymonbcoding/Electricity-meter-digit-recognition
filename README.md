# Electricity-meter-digit-recognition
Project for Deep Learning lessons.

Purpose of this project is recognition of digits from taken photos of electricity meter.

This is not all-purpose solution, because in this project is used specific coordinates, where script proccess to classify digits.

Script "crop.py" creates cropped images from raw photographies' specific spaces from folder "before_processing".

Script "train_test.py" loads images from different folders in "classes", create neural network, train and test it. Finally, make extra test based on photos outside the train or test sets.

Important link to get knowledge about image recognition with TensorFlow and Convolution Neural Networks:
https://www.tensorflow.org/tutorials/images/classification
