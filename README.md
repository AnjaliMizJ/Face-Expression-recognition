# Face-Expression-recognition

In this project, a convolutional neural network (CNN) is build and trained in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). OpenCV is used to automatically detect faces in images and draw bounding boxes around them. Once trained, saved, and exported the CNN, the trained model is directly served to a web interface and perform real-time facial expression recognition on video and image data. 


