## Project: Traffic Sign Recognition Program

Overview
---
In this project I trained convolutional neural networks to classify traffic signs. I used TensorFlow in defining the CNN. The network was trained and validated to classify traffic sign images using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). 

On the test data that comes with the dataset an accuracy of 95.7 percentage was achieved.

The trained model is then tested with random German Traffic Signs found on web.

The Jupyter Notebool "Traffic_Sign_Classifier.ipynb" contains the code along with clear explaination. Also, a detailed explaination on the code and the CNN network is given in "Writeup_project_traffic_sign_classifier.pdf" which is included in the repository.

NOTE: Labels / number that different traffic signs are associated with are given in "signnames.csv", which is also  included in the repository.

The Project
---
The below are the steps followed in the project:
* Load the data set
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report - the PDF file "Writeup_project_traffic_sign_classifier.pdf" included in the repository has detailed explaination of all the above steps.

### Dependencies
This lab requires:

* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

The lab environment can be created with CarND Term1 Starter Kit. Click [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) for the details.

### Dataset and Repository

1. Images from the above mentioned German Traffic Sign Data set are resized to 32x32 images. You can download the dataset from [here](https://s3-us-west-1.amazonaws.com/udacity-selfdrivingcar/traffic-signs-data.zip). Unzip the downloaded file. There should be three files in "pickle" format for training, validation and testing (namely train.p, valid.p, test.p).
2. Clone the project:
```sh
git clone https://github.com/rohilnula/CarND-Traffic-Sign-Classifier-Project.git
cd CarND-Traffic-Sign-Classifier-Project
jupyter notebook Traffic_Sign_Classifier.ipynb
```
3. On the first cell of the Jupyter notebook change the path to training, validation and testing files to the path of the dataset you downloaded. 