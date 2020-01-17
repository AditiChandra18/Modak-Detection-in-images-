I have used Mask Region-based Convolutional Neural Networks.
Task includes following steps:
1. Preparation of dataset and it's annotation
2. Training the dataset
3. Testing the dataset

Since, no dataset on "modak" was available, I have created my own dataset(folder name is "modak") which contains two folders
1. Images (contains 80 images of modak) 
2. Annots(contains the annotation of the respective 80 images)

The first code does the calculation and gives the dimensions of the bounding box of the no. of  annotations done in an image.

The second code is of splitting the image sinto training and testing images and likewise loading the dataset object
To run my code I required an updated version of tensor flow although a continuous internal error (file downloads) kept 
occurring and despite many efforts, it cannot be solved in time. Thus, I could not run the epochs of my code and if given 
more time I will be able to complete this. 

The third code provides the testing of images and finally detect the modak in an image
