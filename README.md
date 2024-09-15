# Clown Nose Filter using POSENET

# Project Description
- This project applies a clown nose filter to a person’s face using the pretrained POSENET model for real-time pose estimation. It detects the position of the nose and overlays a clown nose on it through a web interface.

## Demo
Check out the live demo here:  
[Live Demo](https://shikha246.github.io/Clown-Nose-Filter-App/)

![Clown Nose Filter](images/cn.png)

## Features
- Real-time nose detection using the pretrained POSENET model.
- Clown nose filter applied dynamically to the detected nose position.
- Runs in the browser with real-time webcam feed.

## Technologies Used
- **Machine Learning**: POSENET (for nose detection)
- **Frontend**: HTML, CSS, JavaScript, TensorFlow.js (for integrating POSENET)

## Usage
- Allow access to your webcam when prompted.
- The clown nose will appear on your face once the POSENET model detects the nose position.

## POSENET Model
The pretrained POSENET model is used to detect 17 different Key Points of you body like nose, eyes, shoulders, knees etc... Based on the nose position, the clown nose is dynamically overlaid on the person’s face in real-time using TensorFlow.js.
