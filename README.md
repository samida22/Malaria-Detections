
# Malaria-Detections
Malaria detections using Cnn from scratch
# Steps involved:
### formating the data in desirable format. 
      Dataset consists of parasitized_images and uninfected_images
### preprocessing  data:
      loop into each folder separate the images and each associated labels into lists.
      split the datasets into train and test sets using  sklearn.model_selection
### train the data using CNN
      I have defined simple CNN model for my own purpose it consists of the conv pooling               droupout flatten and dense layera 
      converting the Xtrian into raay before passing to model, batchsizes=64 for 50 epochs 
### use optimizer and loss accuracy measures for good performance extractions
        -used adam optimizer categorical_crossentropy and accuracy metrics
### calculate the test accuracy
    got 95.52% accuracy on test sets

![Screenshot from 2021-06-12 17-54-35](https://user-images.githubusercontent.com/83119874/121775534-0728f100-cba8-11eb-9876-d839a7adf0c7.png)


![Screenshot from 2021-06-12 17-54-13](https://user-images.githubusercontent.com/83119874/121775531-01331000-cba8-11eb-8a3f-f21cb31354c6.png)
