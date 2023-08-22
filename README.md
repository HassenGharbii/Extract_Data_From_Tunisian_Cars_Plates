# License Plate Detection and OCR using Python

This project demonstrates a basic process for detecting license plates in images and extracting text from them using Python. It utilizes OpenCV for image manipulation, EasyOCR for optical character recognition, and Matplotlib for visualization.

## Overview

This project aims to:

1. Read in an image using OpenCV.
2. Convert the image to grayscale and apply filtering.
3. Perform edge detection using the Canny algorithm.
4. Find contours to locate the license plate area.
5. Apply a mask to extract the license plate.
6. Use EasyOCR for text extraction from the license plate.

## Dependencies

- Python 3.x
- OpenCV
- imutils
- EasyOCR
- Matplotlib

Install the required packages using the following command:
```bash
pip install -r requirements.txt

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/license-plate-detection.git
