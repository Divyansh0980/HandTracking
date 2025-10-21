# HandTracking
Python hand tracking module with MediaPipe - Detect hands, track fingers, measure distances, and recognize gestures in real-time

# Hand Tracking Module

A Python-based hand tracking module using MediaPipe and OpenCV for real-time hand detection and gesture recognition.

## Features

- 🖐️ Real-time hand detection and tracking
- 👆 Finger position detection (up/down state)
- 📏 Distance calculation between fingers
- 🎯 Hand landmark identification (21 points per hand)
- 📦 Reusable `handDetector` class for easy integration
- ⚡ High-performance tracking 

## Demo

The module can detect up to 2 hands simultaneously and provides:
- Hand landmarks with connections
- Bounding box around detected hands
- Individual finger state detection
- Distance measurements between any two landmarks
- Real-time FPS display

## Requirements

- Python 3.7+
- OpenCV
- MediaPipe
- NumPy (installed with OpenCV)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Divyansh0980/HandTracking
cd HandTracking
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

### Basic Usage

Run the demo script:
```bash
python HandTracking.py
```

Press `q` to quit the application.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [MediaPipe](https://google.github.io/mediapipe/) by Google for the hand tracking solution
- [OpenCV](https://opencv.org/) for computer vision functionality


Project Link: https://github.com/Divyansh0980/HandTracking
