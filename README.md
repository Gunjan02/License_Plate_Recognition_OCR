# License_Plate_Recognition_OCR
Downloaded the dataset from github link - https://github.com/openalpr/benchmarks/tree/master/endtoend/br

Approach followed for building a Neural Network for OCR from scratch-
1.) Gathering dataset of cars having annotations for license plate.
2.) Preprocessing the images, Converting RGB to Grayscale, Normalizing and other  Computer Vision libraries for smoothening the image which will help further in extracting features from images.
3.) Draw Bounding boxes with the help of Computer vision and the annotations done.
4.) Crop these bounding boxes as these are our Region of Interest.
5.) Finally split the dataset as training and validation and encode the characters for prediction.
6.) Build a CNN + RNN + CTC loss Model and train the data. Finally predict from the trained model using ctc decoder.
