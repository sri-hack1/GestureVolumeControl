# GestureVolumeControl

GestureVolumeControl is a Python-based project that enables volume control using hand gestures. It utilizes computer vision techniques to detect and interpret hand gestures captured through a webcam.

## Features

- Control system volume using hand gestures recognized by the application.
- Adjustable sensitivity settings for gesture recognition.
- Compatible with Linux systems (Note: alsaaudio dependency is for Linux only).

## Dependencies

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)
- [alsa](https://github.com/larsimmisch/pyalsaaudio) (Linux only)

## Getting Started

To get started with GestureVolumeControl, follow these steps:

1. Ensure you have a webcam connected to your computer.
2. Clone this repository to your local machine.
``` bash
git clone https://github.com/sri-hack1/GestureVolumeControl.git
```
4. Install the required dependencies by running:
``` bash
pip install -r requirements.txt
```
5. Run the `Volume_control.ipynb` file.
6. Read the 'Usage' for understanding the use.

## Usage

- Hold your hand in front of the webcam.
- By adjusting the distance of your thumb's tip and index finger, volume will be controlled
- Adjust the sensitivity settings as needed for optimal gesture recognition.

## Compatibility

- This project is designed for Linux systems due to the dependency on the `alsa` library for audio control.
- Windows users may need to explore alternative audio control libraries or adapt the code accordingly. They can use:-
``` bash
pip install pycaw
```

## Contributing

Contributions to GestureVolumeControl are welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Test your changes thoroughly.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


