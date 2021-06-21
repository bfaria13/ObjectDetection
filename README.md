# Object Detection from Images

> A single image can contain different objects, so the main aim here is implementing a code able to get sub-images using Selective Search, filtering them, and returns the classification of each object present in an input image.



# First Notebook - _ObjectDetection_1.ipynb_:

>  The file ObjectDetection_1.ipynb contains all implemented code to classify sub-images generated for a single input image using Selective Search and/or Contours.

> **Two pretrained neural networks will be used here: ResNet50 and VGG19.**

> The **imgs** folder contains images to use as example.

> Three folders can be created: **selserach**, **filtered** and **contours** containing images from selective search, images filtered, and images from contours.

> **This Notebook is divided into 3 parts:**

* Part 1 : getting sub-images from an input image using selective search;

  * ​	The code can generate a folder **selsearch** containing all sub-images saved as jpg files.

    

* Part 2 : classifying sub-images with pre-trained models;

  * ​	The pre-trained models are loaded and used in an image classification task.

    

* Part 3 : getting sub-images from an input image using contours approach.

  * ​	The code can generate a folder **contours** containing all sub-images saved as jpg files.



# Second Notebook - _ObjectDetection_2.ipynb_:

>  The file ObjectDetection_2.ipynb contains all implemented code from neural network creation to classification of sub-images generated for a single input image using Selective Search and/or Contours.

> **A neural networks will be created based on Ciphar100 dataset.**

> It's convenient to use Google Colab to train the model due to gpu acceleration.

> The images from **selsearch** folder will be used to predict labels based on this model.

>  **This Notebook is divided into 2 parts:**

* Part 1 : basic neural network implementation based on dataset cifar100;

  * ​	the code could be used in google colab.

    

* Part 2 : classifying sub-images using this own model.

  * ​	using sub-images generated previously as input for the own model.

  * ​	model saved as json and h5 is requeried! Files used as example: _cifar100_example.json_ and _cifar100_example.h5_

    

> **The main aim here (this notebook!) is to demonstrate how to implement a neural network of your own to analyze sub-images, not the efficiency or any other metric between different models.**



## 3) Extra files:

* Notebook _Contours.ipynb_ contains some examples of how to contours objects in images.



**Author:** _Bruna Faria_, Experience with ML/DL and exploring data. PhD student in Computational and Data Science and Engineering (Skoltech). 

**Github:** [bfaria13 (Bruna Faria) (github.com)](https://github.com/bfaria13)

