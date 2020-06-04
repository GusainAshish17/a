# Identify the INDIAN classical dance form
Classifying 8 different dance forms using transfer learning, while utilizing pre-trained model ResNet50.


## Problem statement
```
This International Dance Day, an event management company organized an evening of Indian classical dance 
performances to celebrate the rich, eloquent, and elegant art of dance. After the event, the company 
plans to create a microsite to promote and raise awareness among people about these dance forms. 
However, identifying them from images is a difficult task.

You are appointed as a Machine Learning Engineer for this project. Your task is to build a deep learning 
model that can help the company classify these images into eight categories of Indian classical dance.
```


## Note
```
The eight categories of Indian classical dance are as follows:
Manipuri
Bharatanatyam
Odissi
Kathakali
Kathak
Sattriya
Kuchipudi
Mohiniyattam
```

### Project Structure:
* **lanes**:This folder contains files related to lane detection only.
* **tf-color**: This folder contains files related to traffic light detection and detect the colour and accordingly give instructions to the driver.
* **tracked**: This folder contains detection and tracking algorithm for the vehicles.
* **untracked**: Detection and visualization only
* **utils**: contains various functions that are used continuously again and again for different frames.
* **estimations**: Detect pedestrians and vehicles too close to us that may cause collision.
* **cropping**: Cropping frames using drag and drop or clicking points.
* **display**: All the gifs shown above are stored here.

## Data Description

Column Name | Description
------------- | -------------
Image  | Name of Image
Target  | 	Category of Image ['manipuri','bharatanatyam','odissi','kathakali','kathak','sattriya','kuchipudi','mohiniyattam']

This data set consists of two columns shown above:
The data folder consists of two folders and two .csv files. The details are as follows:
* **train** : Contains 364 images for 8 classes ['manipuri','bharatanatyam','odissi','kathakali','kathak','sattriya','kuchipudi','mohiniyattam']
* **test**: Contains 156 images
* **train.csv**: 364 x 2
* **test.csv*8: 156 x 1




## Results 
```

```
