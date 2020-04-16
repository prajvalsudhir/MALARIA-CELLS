# MALARIA-CELLS
CNN trained on real image files to detect Malaria infected blood cells

The dataset contains 2 folders - Infected - Uninfected

And a total of 27,558 images.

This Dataset is taken from the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/

page hosts a repository of segmented cells from the thin blood smear slide images from the Malaria Screener research activity. 

sample images:

![sample](https://user-images.githubusercontent.com/26242097/50046086-713da980-00c3-11e9-9c79-db215df220e2.jpg)

* Image data generator is used to process and manipulate the images to build a robust model

* The Model has been trained using Keras and Tensorflow 2.0 frameworks

* Binary classification model trained to predict labels:'parasitized': 0, 'uninfected': 1

* The model has training and validation accuracy of approximately 95%
