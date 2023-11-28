# Face Recognition 

This project uses OpenCV, dlib, and face_recognition libraries to perform face recognition in real time on camera . Follow the instructions below to set up and run the project.

## Prerequisites

Before running the project, make sure you have the following installed:

- Python 3.x
- pip (Python package installer)

## Installation

1. Install the required libraries:

    ```bash
    pip install opencv-python
    pip install dlib
    pip install face_recognition
    ```

## Usage

1. Add an image of the person to the `images` directory.

2. Run the `main.py` file:

    ```bash
    python main.py
    ```

3. The application will open a video stream with face recognition. The recognized person's name will be displayed on the camera and the rest as unknown.

## Additional Notes

- Ensure that the image file in the `images` directory contains a clear face of the person you want to recognize.
- One image of the person is enough.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated.

## License

This project is licensed under the [MIT License](LICENSE).

