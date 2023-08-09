
# Sign Language Live Detection

This project is aimed at real-time sign language detection using the webcam and machine learning techniques. It leverages the MediaPipe library for hand tracking and a pre-trained model to classify sign language gestures.

## Features

- Real-time hand tracking using the MediaPipe library.
- Classification of sign language gestures using a pre-trained model.
- Display of predicted actions and accuracies.
- Display of recent predicted actions for context.

## Usage

1. Clone this repository:

    ```sh
    git clone https://github.com/your-username/sign_language_detection.git
    cd sign_language_detection
    ```

2. Run the `app.py` script to start the live sign language detection:

    ```sh
    python app.py
    ```

3. The webcam feed will open, and the application will start predicting sign language gestures in real-time.

4. The predicted actions, their accuracies, and the last N predicted actions will be displayed on the screen.

5. To stop the application, press `q`.

## Model

The model used for sign language classification is loaded from the `model.json` and `model.h5` files. The model architecture is described in JSON format, and the trained weights are loaded from the H5 file.

## Dependencies

- mediapipe
- keras
- numpy
- opencv-python

## Acknowledgments

This project utilizes the MediaPipe library for hand tracking and was inspired by the desire to promote accessibility through technology.
This project is based on the work of CoderSammy(https://github.com/codersammy/Sign_Language_Classification), and was cloned from  https://lnkd.in/d7eBAP7H.



---

Feel free to customize this template with additional sections or information specific to your project. Providing clear installation and usage instructions, along with explanations of the project's features, will help others understand and use your project effectively.
