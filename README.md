# Car Number Plate Detection

This is the README file for the "Car Number Plate Detection" project. The project focuses on detecting and localizing car number plates in real-time using computer vision techniques.

## Project Overview

Car number plate detection is a crucial component in various applications, such as automated toll collection, parking management, and traffic monitoring. In this project, we use a pre-trained Haar Cascade classifier specifically trained for Russian car number plates.

## How to Run

To run the car number plate detection script:

1. Ensure you have OpenCV installed. You can install it using `pip`:

   ```bash
   pip install opencv-python
   ```

2. Run the script using Python:

   ```bash
   python numberplate.py
   ```

   This will start the webcam feed, and the script will attempt to detect and highlight car number plates in real-time.

## Features

- Real-time car number plate detection using a Haar Cascade classifier.
- Drawing rectangles around detected number plates.
- Displaying a region of interest (ROI) containing the detected number plate.
- Saving detected number plates as images when the 's' key is pressed.

## Key Bindings

- Press 's' to save a detected number plate as an image in the "plates" directory.
- Press 'q' to exit the application.

## Project Structure

The project consists of the following files:

- `numberplate.py`: The main Python script for car number plate detection.
- `model/haarcascade_russian_plate_number.xml`: The pre-trained Haar Cascade classifier for Russian car number plates.
- `plates/`: The directory where detected number plates are saved.


## Acknowledgments

- OpenCV for computer vision capabilities.
- The dataset and pre-trained model for car number plate detection.
- The open-source community for valuable resources and inspiration.

Feel free to reach out for any questions or suggestions related to this project. Happy number plate detection!
