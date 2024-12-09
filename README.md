# Real-Time Sign Language Detection Using CNN

202403_Intro to Computer Vision_CSCI_6527_10_Final Project

## Acknowledgment
This blog post was created by Ritwika Das (GWID: G30941802) and Aditi Vyas (GWID: G40802010) under the guidance of Professor Robert Pless for the course Introduction to Computer Vision (CSCI 6527_10).

## Main Idea
The main focus of this project is to detect sign language in real-time using Convolutional Neural Networks (CNN).

## Process
Follow these steps to replicate or contribute to the project:
1. We set the hand histogram for creating gestures. Once we got a good histogram, we saved it in the code folder.
2. We added gestures and labeled them using OpenCV which captured inputs from the webcam.
3. We then added different variations to the captured gestures by flipping all the images.
4. Then we splited all the captured gestures into training, validation, and test sets.
5. All the gestures were then viewed to ensure they were correctly captured and labeled.
6. The CNN model was then trained using Keras.
7. The application was launched which will use the system's webcam to interpret the trained American Sign Language gestures.

## Current Progress
As of now, we have completed each of the steps mentioned in the process. We are currently working on improving the model's accuracy as the project is not yet able to predict with high reliability. Future steps include addressing these prediction issues and potentially implementing text-to-speech conversion to enhance the application's accessibility.

## Future Work
Once we achieve satisfactory prediction accuracy, we plan to explore the possibility of integrating a text-to-speech system to make the application more useful for real-world applications.
