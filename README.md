# American-sign-language (Hand Gesture Classification Project)

##Overview:

This project is a hand gesture classification system designed to recognize and classify hand gestures in real-time using computer vision and deep learning techniques. The system captures video frames from a camera, detects and tracks a user's hand, and then classifies the observed hand gesture using a pre-trained model.

##Features:

1. Real-time Hand Gesture Classification:
        The system processes video frames in real-time, identifying and classifying hand gestures on the fly.
2. MobileNet-based Model:
        The classification model is based on the MobileNet architecture, optimized for efficiency and suitability on mobile and embedded devices.
3. User-friendly Interface:
        The testing script provides a user-friendly interface with visualizations, including bounding boxes around detected hands and predicted gesture labels.
        Getting Started

##Prerequisites
>Python 3.x
>Required Python libraries (specified in requirements.txt)


### "If you want to extend the dataset or train your own model:" **

##Run the data collection script:

python collection_file.py
Follow on-screen instructions to capture and save hand gesture images.
Testing

##Run the testing script:

python testing_file.py
The real-time hand gesture classification will be displayed on the screen.

##Model and Dataset
The pre-trained hand gesture classification model is included in the model directory (keras_model.h5).
The dataset used for training the model is located in the data directory.
Contributing

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and submit a pull request.




https://github.com/priyanka-neggi/sign-language-American-/assets/117040051/53d89f08-28cf-4e56-981c-69cc964fcd5a


Acknowledgments

cvzone: Used for hand tracking and classification modules.
MobileNet: The efficient neural network architecture used for hand gesture classification.
Contact

For questions or inquiries, please contact negip105@gmail.com.



