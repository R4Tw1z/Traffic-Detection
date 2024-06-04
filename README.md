# Traffic-Sign-Detection
Real-time traffic sign recognition in Python (built by R4tW1z).


# Real-Time Traffic Sign Recognition with Python 🚦🐍

This project implements a real-time traffic sign recognition system using Python and OpenCV. It leverages a pre-trained deep learning model to identify traffic signs from webcam footage. 📹

## Features 🌟

- **Real-time processing**: Analyzes traffic signs from a live video feed. 🕒
- **Traffic sign classification**: Predicts various traffic signs like speed limits, warnings, and directional signs. 🚸🚫⛔
- **Visual output**: Overlays the predicted sign name on the video frame. 🖼️

## How it Works 🛠️

### Libraries and Model 📚

- Utilizes OpenCV for video capture and image processing. 📷
- Leverages TensorFlow for deep learning functionalities. 🧠
- Employs a pre-trained traffic sign recognition model (Traffic.h5) for classification. 🎓

### Class Name Mapping 🗺️

- Maps predicted class indices from the model to human-readable traffic sign names using a dictionary (class_names_R4Tw1z). 📖

### Webcam Integration 🎥

- Initializes webcam capture to access real-time video frames. 🖥️

### Traffic Sign Recognition Loop 🔁

- Continuously captures frames from the webcam. 🔄
- Preprocesses each frame (resizing, format conversion). 🧮
- Feeds the preprocessed frame to the model for prediction. 🎯
- Retrieves the predicted traffic sign name based on the model's output. 🏷️
- Overlays the predicted sign name on the video frame for visualization. 👁️
- Displays the video stream with the overlaid sign name. 📺

## Built by R4tW1z 🛠️👷

This project showcases a basic real-time traffic sign recognition system. Note that the pre-trained model's accuracy may vary depending on the training data and real-world conditions. 🌐

Feel free to explore and contribute! 🚀👩‍💻👨‍💻


