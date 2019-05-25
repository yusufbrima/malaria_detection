

Project Title
Deep Residual Convolutional Neural Network Malaria Detection from microsopic bllo cell images

Experiment with Deep Residual Convolutional Neural Network to classify microscopic blood cell images (Uninfected, Parasitized)
Utiling ResNet,Deep Residual Learning for Image Recognition (He et al, 2015) architecture. 
Uses Keras with a Tensorflow backend. 
We varied the model parameters to observe the effects on performance of on the result.

Prerequisites
Python 3.6
Tensorflow backend 
Numpy
Scikit-learn
Matplotlib
imutils

Dataset
https://ceb.nlm.nih.gov/proj/malaria/cell_images.zip


Buiding the dataset
cd whatever-you-named-your-directory
mkdir malaria
cd malaria
wget https://ceb.nlm.nih.gov/proj/malaria/cell_images.zip
unzip cell_images.zip
python build_dataset.py

Training the Model
python train_model.py

Colab Notebook
https://drive.google.com/open?id=15YPcWeEiehxfda9rEdP5SpeSRT-0uPug

Presentation
https://www.slideshare.net/YusufBrima/detecting-malaria-using-a-deep-convolutional-neural-network


Authors
Yusuf Brima
Jargis Ahmed

License
This project is licensed under the MIT License
