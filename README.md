# Image Classification

This is an image classification program that predicts given images based on 10 classes listed below:
- Plane, Car, Bird, Cat, Deer, Dog, Frog, Horse, Ship and Truck
It uses a Convolutional Neural Network to train on the training dataset, 
and predicts an ouput with over 70% accuracy.
The cifar10 Dataset library from Keras was used to train the model of this application.


# Installation
 1. Download and install Python 3 or higher from <a href="https://www.python.org/downloads/">here</a>
 2. Clone this repo to your local machine using:
  ```bash
 git clone https://github.com/Tamer7/Web-imageclassifer.git
 ```
 3. Download the required packages by typing:
 ```bash
pip install -r requirements.txt
```
 4. Discard the Machine Learning model folder and use only the:
 ```bash
webapplication folder
```



# Usage
 1. To run the django server follow these steps below:
 ```bash
a. cd into the webapplication folder (cd webapplication)
b. run the following command to start the server (python manage.py runserver)
c. Nagivate to the localhost shown in the terminal (in my case it is "http://127.0.0.1:8000/")

```

## Uploading images and getting predictions
2. Once navigated to your localhost link you will be presented with this page below:
 ![](/Images/index_image.PNG)
 
3. Select on the upload file and upload your desired picture:
 ![](/Images/upload_image.PNG)
 
4. The result gets processed and outputed with the prediction
 ![](/Images/prediction_image.PNG)



# Model Accuracy
The Model used and developed is a CNN neural network, it was trained on 60,000 images, 50,000 training and 10,000 testing.
6,000 images where trained per class. 
The model was compiled using adam optimizer and was trained on 15 epcohs as the result shown below:
 ![](/Images/model_training_image_15_epochs.PNG)
 
 - Model training accuracy reached to : 80.2 percentage
 - Model testing accuracy reached to : 70.02 percentage

  




# Built With

- Python 
- Tensorflow Library
- Django

# DataSet Used
- Cifar10 dataset from the keras library




# Authors

- Tamer Algarmakany











        

 
 
 
 
 
        
