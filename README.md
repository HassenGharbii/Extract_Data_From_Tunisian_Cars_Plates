# License Plate Detection with OCR and Python

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
```
## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/license-plate-detection.git
```

## Steps
1. Read and Preprocess Image: The script reads in an image and converts it to grayscale using OpenCV.

2. Filtering and Edge Detection: A bilateral filter is applied to reduce noise, and edge detection is performed using the Canny algorithm to detect edges in the image.

3. Contour Search: Contours are identified using OpenCV's findContours function. The script then filters the contours to find the potential license plate area.

4. Mask Application: A mask is created to isolate the license plate area. The mask is then applied to the original image to extract the license plate.

5. Text Extraction: EasyOCR is used to perform optical character recognition on the extracted license plate region. Detected text is printed in the console.
