# Sign Recognition System 

This repository contains code for a real-time sign language recognition system. The system is designed to take sign language gestures as input and convert them into real sentences and audio files using machine learning algorithms.

## Getting Started
To get started with the sign recognition system, follow these steps:

1. Run `sign_recog_for_further.py` to train the data and test it in real-time.
2. Once the model weights are ready, run `sign_recog_run.py` to import your data and use the `sentence_creator_run` model to create sentences for the recognized signs.

## Usage
### Training Data
The training data consists of sign language gestures that you want to recognize. Ensure that your training data covers a wide range of gestures to improve recognition accuracy.

### Testing in Real-Time
Use the `sign_recog_for_further.py` script to test the system in real-time. This script will capture live video input and recognize the gestures using the trained model.

### Generating Sentences and Audio Files
After training the model and testing it in real-time, use the `sign_recog_run.py` script to import your data and generate sentences for the recognized signs. The system will also generate audio files corresponding to the recognized sentences.

## Dependencies
- Python 3.x
- Machine Learning Libraries (e.g., TensorFlow, Scikit-learn)
- OpenCV
- NumPy

## Contributing
Contributions to improve the sign recognition system are welcome. Feel free to fork this repository, make changes, and submit pull requests.

## Acknowledgements
- Special thanks to the contributors and developers of the machine learning libraries used in this project.
- This project was inspired by the need for accessible communication tools for the hearing impaired community.
