# Hand Tracking

## Overview

This hand tracking project utilizes the MediaPipe library and OpenCV to detect and track hands in real-time using a webcam. The project includes two main scripts: `Basics.py` and `HandTrackingModule.py`. The first script is a simple implementation of hand tracking, while the second script encapsulates the functionality into a reusable class.

## Requirements

- Python 3.x
- OpenCV (`cv2`) library
- MediaPipe library (`mediapipe`)

To install the required libraries, use the following:

```bash
pip install opencv-python
pip install mediapipe
```

## Usage

### `Basics.py`

1. Open a terminal window and navigate to the project directory.
2. Run the script using the following command:

   ```bash
   python Basics.py
   ```

3. The webcam feed will open, and hand landmarks will be displayed in real-time.
4. Press 'q' on the keyboard to exit the application.

### `HandTrackingModule.py`

1. Open a terminal window and navigate to the project directory.
2. Run the script using the following command:

   ```bash
   python HandTrackingModule.py
   ```

3. The webcam feed will open, and hand landmarks will be displayed in real-time.
4. Press 'q' on the keyboard to exit the application.

## Functionality

### `Basics.py`

- Detects and tracks hands in the webcam feed.
- Displays the landmarks of the detected hands.
- Calculates and displays the frames per second (FPS) of the webcam feed.

### `HandTrackingModule.py`

- Encapsulates hand tracking functionality into a `HandDetector` class.
- Provides methods to find hands and their positions.
- Displays the landmarks of the detected hands.
- Calculates and displays the frames per second (FPS) of the webcam feed.

## Customization

You can customize the `HandDetector` class in `HandTrackingModule.py` by adjusting parameters such as `maxHands`, `modelC`, `detectionCon`, and `trackCon` to achieve different levels of hand detection accuracy and tracking sensitivity.

Feel free to modify and extend the project according to your specific requirements.

## Dependencies

- [OpenCV](https://opencv.org/): An open-source computer vision and machine learning software library.

- [MediaPipe](https://mediapipe.dev/): A popular library for building applications using various perception modalities, such as hands, face, and pose.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
