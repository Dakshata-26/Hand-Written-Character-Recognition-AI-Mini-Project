# Hand-Written-Character-Recognition-AI-Mini-Project

## ABSTRACT 
In todays’ world advancement in sophisticated scientific techniques is pushing further the limits of human outreach in various fields of technology. One such field is the field of character recognition commonly known as HCR (Handwritten Character Recognition). 
Handwritten character recognition (HCR) is a challenging learning problem in pattern recognition, mainly due to similarity in structure of characters, different handwriting styles, noisy datasets and a large variety of languages and scripts. 
This project, ‘Handwritten Character Recognition’ is a software algorithm project to recognize any hand written character that is, English alphabets from A-Z, efficiently on computer with input is either an old optical image or currently provided through touch input, mouse or pen. 

## PURPOSE OF THE PROJECT 
Advantage of HCR systems is that it can reduce the data entry time, storage space required by documents. Fast retrieval is an alternative advantage.  
HCR can be used in diverse fields like banking field where checks can be processed without human interruption and to digitize paper documents in legal industries. 
 
## OBJECTIVE OF THE PROJECT 
The objective of this project is to identify handwritten characters with the use of neural networks. We have to construct suitable neural network and train it properly. The program should be able to extract the characters one by one and map the target output for training purpose. After automatic processing of the image, the training dataset has to be used to train “classification engine” for recognition purpose. 
 
## Project Prerequisites
Below are the prerequisites for this project: 
-	Python (3.7.4 used) 
-	IDE (Jupyter used) 

## Required frameworks are 
-	Numpy (version 1.16.5) 
-	cv2 (openCV) (version 3.4.2) 
-	Keras (version 2.3.1) 
-	Tensorflow (Keras uses TensorFlow in backend and for some image preprocessing) (version 2.0.0) 
-	Matplotlib (version 3.1.1) 
-	Pandas (version 0.25.1) 

## Dataset Details 
The dataset contains 26 folders (A-Z) containing handwritten images in size 2828 pixels, each alphabet in the image is centre fitted to 2020-pixel box. All present in the form of a CSV file. 
Each image is stored as Gray-level 
Handwritten character recognition dataset 
 
## INTRODUCTION 
This project, ‘Handwritten Character Recognition’ is a software algorithm project to recognize any hand written character that is, English alphabets from A-Z, efficiently on computer with input is either an old optical image or currently provided through touch input, mouse or pen. 
This we are going to achieve by modelling a neural network that will have to be trained over a dataset containing images of alphabets. 
The handwritten character recognition is the capability of computer applications to recognize the human handwritten characters. It is a hard task for the machine because handwritten characters are not perfect and can be made with many different shapes and sizes. The handwritten character recognition system is a way to tackle this problem which uses the image of a character and recognizes the character present in the image. 
The idea is to device efficient algorithms which get input in digital image format. After that it processes the image for better comparison. Then after the processed image is compared with already available set of font images. The last step gives a prediction of the character in percentage accuracy. 
 
## APPROACH  
The computation code is divided into the next categories:  
-	Pre-processing of the image  
-	Feature extraction  
-	Creating an Artificial Neural Network  
-	Training & Testing of the network  
-	Recognition 
