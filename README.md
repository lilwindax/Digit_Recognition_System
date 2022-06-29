# Digit Recognition System 

## Backpropagation based Artificial Neural Network implementation of Digit Recognition System

### Context 
Computers have struggled to interpret handwritten text on paper documents. Converting Hand written characters to digital ones is a challenge. Despite the rise in digital documentation, there are still a lot of paper documents across the globe that we need computers to decipher. Alongside this there are a number of different Computer Vision based applications that require detection and interpretation of Hand written characters. 

### Objective 
Train a Backpropagation based Artificial Neural Network model from scratch to identify handwritten numbers. 

### Dataset
The dataset used in this project is a custom dataset that contains 40 images for digits from 0 to 9 

### Methodology

Image pre-processing: 
      
        - Read Image 
        - Resize all images to a uniform size 
        - Apply gaussian filter over image
        - Delcare CLAHE parameters and apply over image

