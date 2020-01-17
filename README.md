# Modak-Detection-in-images-
I have used Mask Region-based Convolutional Neural Networks.A Mask R-CNN model can be fit from scratch, although like other computer vision applications, time can be saved and performance can be improved by using transfer learning. Object detection is a task in computer vision that involves identifying the presence, location, and type of one or more objects in a given image.

It is a challenging problem that involves building upon methods for object recognition (e.g. where are they), object localization (e.g. what are their extent), and object classification (e.g. what are they).

Mask R-CNN is a sophisticated model to implement, especially as compared to a simple or even state-of-the-art deep convolutional neural network model. Instead of developing an implementation of the R-CNN or Mask R-CNN model from scratch, we can use a reliable third-party implementation built on top of the Keras deep learning framework.

Task includes following steps:
1. Preparation of dataset and it's annotation
2. Training the dataset
3. Testing the dataset

Since, no dataset on "modak" was available, I have created my own dataset which contains two folders
1. Images (contains 80 images of modak)
2. Annots(contains the annotation of the respective 80 images) I have done the annotation using labellmg (https://github.com/tzutalin/labelImg)

The first code does the calculation and gives the dimensions of the bounding box of the no. of annotations done in an image.

The second code is of splitting the image sinto training and testing images and likewise loading the dataset object To run my code I required an updated version of tensor flow although a continuous internal error (file downloads) kept occurring and despite many efforts, it cannot be solved in time. Thus, I could not run the epochs of my code and if given more time I will be able to complete this. This liberary was required  https://github.com/matterport/Mask_RCNN/blob/master/mrcnn/utils.py to import so that a new dataset class could be created.

The third code provides the testing of images and finally detect the modak in an image

The results are:
1. Output of calculation of dimension of bounding box (example)
![dimension of bounding box output](https://user-images.githubusercontent.com/37157534/72637806-18a4a400-3988-11ea-828a-b51f3fae1a14.JPG)


2. Output of Develop ModakDataset Object
![Capture](https://user-images.githubusercontent.com/37157534/72637416-463d1d80-3987-11ea-9877-80bdbef00eda.JPG)
