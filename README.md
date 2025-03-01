# Image Resizing and Conversion Script

## Overview
This script utilizes OpenCV to resize an image by 50% of its original dimensions and save it in a different format.

## Features
- Reads an image from the specified source file.
- Resizes the image to 50% of its original width and height.
- Saves the resized image to a new file with a different format.

## Requirements
- Python 3.x
- OpenCV (cv2 library)

## Installation
Before running the script, ensure you have OpenCV installed. You can install it using pip:

```bash
pip install opencv-python
```

## Usage
1. Place the image file (e.g., `new image.jpg`) in the same directory as the script.
2. Update the `source` and `destination` file paths in the script if needed.
3. Run the script:

```bash
python script.py
```

## Code Explanation
- The script reads an image using `cv2.imread()`.
- It calculates the new dimensions by reducing the width and height by 50%.
- The `cv2.resize()` function resizes the image.
- The `cv2.imwrite()` function saves the resized image in the new format.

## Output
- The resized image will be saved as `newImage.png` in the same directory.

