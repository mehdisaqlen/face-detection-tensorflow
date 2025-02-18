# Face Detection with TensorFlow.js

This project demonstrates face detection using TensorFlow.js and the BlazeFace model. The application captures video from the user's webcam and detects faces in real-time.

## Features

- Real-time face detection using the BlazeFace model
- Simple and clean UI with a dark theme
- Displays the number of faces detected

## Getting Started

### Prerequisites

To run this project, you need the following:

- A modern web browser with JavaScript enabled
- A webcam

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/face-detection-tensorflowjs.git
```

2. Navigate to the project directory:

```bash
cd face-detection-tensorflowjs
```

3. Open `index.html` in your web browser.

### Usage

1. Open the `index.html` file in your web browser.
2. Allow the browser to access your webcam.
3. Click the "Start Face Detection" button to begin detecting faces.

## Code Overview

- **index.html**: The main HTML file that sets up the UI and includes the necessary scripts and styles.
- **style.css**: Contains the CSS styles for the application, creating a dark-themed UI.
- **script.js**: The JavaScript file that initializes the webcam, loads the BlazeFace model, and performs face detection.

## Technologies Used

- [TensorFlow.js](https://www.tensorflow.org/js) for running machine learning models in the browser
- [BlazeFace](https://github.com/tensorflow/tfjs-models/tree/master/blazeface) for face detection
- HTML, CSS, and JavaScript for the web interface

## Screenshots

![screenshot](path-to-screenshot.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- TensorFlow.js team for providing the powerful library for running ML models in the browser
- BlazeFace model developers for their face detection model
