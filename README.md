# Poker Hand Detector

This repository contains tools for detecting and classifying poker hand combinations using a computer's camera. It consists of three files:

## 1. Poker_hand_detector_training.ipynb

The `Poker_hand_detector_training.ipynb` file is used to train the poker hand detection model. It utilizes YOLO v8 technology and card images obtained from Roboflow platform. After the training process, the model is saved and used in the subsequent steps of detection and classification.

## 2. poker_hand_detector_functions.ipynb

The `poker_hand_detector_functions.ipynb` file contains the `findPokerHand` function, which allows for recognizing the poker hand combination based on the provided cards. The function converts the card symbols into numerical values, sorts them, and determines the type of hand combination they form. It returns the name of the recognized combination. The file also includes examples of how to use the function.

## 3. poker_hand_detector.ipynb

The `poker_hand_detector.ipynb` file enables the detection of cards using a computer's camera and their classification using the previously trained model. Additionally, it utilizes the `findPokerHand` function to determine the recognized hand combination. The detection and classification process is performed in real-time. It is also possible to take a photo using the computer's camera and process it to detect the cards and determine the combination.

## Usage

1. Make sure you have the required libraries and runtime environment installed.
2. Run `Poker_hand_detector_training.ipynb` to train the card detection model.
3. Use the obtained model in the `poker_hand_detector.ipynb` file to detect and classify cards in real-time.

Provide the correct file paths and resources in the code to reflect your own environment.

*Note: This project is an example and may require adjustments depending on your own needs and configuration.*

For any questions or issues, please contact the author.

Technologies Used:
- YOLO v8 for object detection
- OpenCV for image processing
- cvzone for graphical overlays
- Python for coding

Card images were obtained from [Roboflow](https://roboflow.com/).

