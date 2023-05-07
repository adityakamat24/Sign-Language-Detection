# Sign-Language-Detection

This project allows users to use a computer vision system to detect and recognize sign language in real-time. The system captures multiple images of each sign to create a dataset, preprocesses the data, and trains a neural network model to recognize the signs. This project can be helpful for people who are deaf, hard of hearing, or unable to speak.

**Features**  
**Real-time sign detection:** the system uses a computer vision algorithm to detect signs in real-time.  
**Dataset creation:** the system captures multiple images of each sign to create a dataset for training.  
**Preprocessing:** the dataset is preprocessed to prepare it for training.  
**Neural network training:** the preprocessed dataset is used to train a neural network model to recognize the signs.  


**How it works**  
The sign language detection system is built using Python and the Tkinter GUI toolkit. It uses the OpenCV library for computer vision and image processing, and the TensorFlow library for deep learning.

The system captures signs using a webcam, and multiple images of each sign are captured to create a dataset. The dataset is then preprocessed to prepare it for training, which involves resizing the images, converting them to grayscale, and normalizing the pixel values. The preprocessed dataset is then used to train a neural network model using TensorFlow.

Once the model is trained, it can be used to detect signs in real-time using the webcam. The system uses the OpenCV library to process the images and detect signs, and then applies the trained neural network model to recognize the signs.
