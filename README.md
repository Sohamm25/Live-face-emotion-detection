# Real-time Facial Emotion Recognition using OpenCV and DeepFace

This project implements a real-time facial emotion detection system using the `DeepFace` library and OpenCV. It captures video from your webcam, detects faces, and predicts the emotions associated with each face, displaying the labels in real-time. This is one of the simplest and most effective implementations for real-time emotion monitoring.

**Give a ⭐ if you found this project useful!**

_Made with ❤️ by [Soham Pawar](https://github.com/Sohamm25)_

## Dependencies

- [DeepFace](https://github.com/serengil/deepface): A powerful deep learning library for facial analysis, enabling emotion detection using pre-trained models.
- [OpenCV](https://opencv.org/): An open-source computer vision library used for capturing and processing video frames.

## Usage
### Initial steps:
- Git clone this repository Run: `git clone https://github.com/manish-9245/Facial-Emotion-Recognition-using-OpenCV-and-Deepface.git`
- Run: `cd Facial-Emotion-Recognition-using-OpenCV-and-Deepface`
1. Install the required dependencies:
   - You can use `pip install -r requirements.txt`
   - Or you can install dependencies individually:
      - `pip install deepface`
      - `pip install tf_keras`
      - `pip install opencv-python`

2. Download the Haar cascade XML file for face detection:
   - Visit the [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades) and download the `haarcascade_frontalface_default.xml` file.

3. Run the code:
   - Execute the Python script.
   - The webcam will open, and real-time facial emotion detection will start.
   - Emotion labels will be displayed on the frames around detected faces.