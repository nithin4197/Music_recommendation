# Emotion Detection and Song Recommendation

This program uses facial emotion detection to recommend songs based on the detected emotion. It captures video from the webcam, analyzes the facial expressions in real-time, and recommends songs accordingly. The user can choose to play music based on either the gender or the dominant emotion detected.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- DeepFace
- Tkinter
- Playsound
- Pygame

## Installation

1. Install the required Python packages:

pip install opencv-python deepface tkinter playsound pygame


2. Download the pre-trained deep learning models for face detection and emotion recognition. The xml file is given in the repository


3. Prepare the music files corresponding to different emotions (e.g., happy, sad, angry, neutral). Ensure they are in the MP3 format and name them accordingly.

## Usage

1. Run the `Music recommendation using facial recognition.ipynb` .
2. Enter your name in the provided text field.
3. Click the "Capture Emotion" button to start the webcam and detect facial expressions.
4. Select either "Gender" or "Emotion" from the radio buttons to choose the criteria for playing music.
5. Enjoy the recommended songs based on the detected emotions or gender.

## Troubleshooting

- If the webcam is not detected or there are errors during execution, ensure that your webcam is connected and accessible. You may need to grant permission for the program to access the webcam.
- If the program fails to load the required pre-trained models, double-check the paths to the XML files and make sure they are correctly specified.

## Contributors

- [Your Name](https://github.com/yourusername)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
