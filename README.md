A small project to recognize digits.
All images(mnist and in TrainImages) are 28*28 pixels and in gray scale
TrainImages directory contains pictures whose data is retrieved and converted into the same format as that in mnist, the two datasets are then concatonated and are used to train the model.
Sequential model from tensorflow is used, layers are added, the model is compiled and trained. Use greater number of epochs for better model.
The model is then tested on images form TestImages. Feel free to just use mnist or add more images.
ensure tensorflow, numpy, sklearn, matplotlib are installed.