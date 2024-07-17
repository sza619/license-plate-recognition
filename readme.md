# License Plate Recognition App

This Streamlit application detects and recognizes license plates in images using OpenCV, NumPy, Imutils, EasyOCR, and Pillow libraries.

### Features:

- Upload an image containing a vehicle with a visible license plate.
- Detects the license plate using contour detection and extracts the plate text using EasyOCR.
- Displays the processed image with the detected license plate and its corresponding text.

### Project Structure:

- **`app.py`**: Main Streamlit application file that handles image upload, processing, and display.
- **`requirements.txt`**: Lists all Python dependencies required for the project.
- **`setup.sh`**: Shell script to set up the project environment and dependencies.
- **`README.md`**: This file, providing an overview of the project, its features, and instructions.

### Installation:

1. Clone the repository:

   ```
   git clone <repository-url>
   cd license-plate-recognition
   ```

2. Install dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

### Usage:

- Run the Streamlit app locally:
  ```
  streamlit run app.py
  ```
- Open your browser and go to the URL provided by Streamlit.

### Dependencies:

- **Streamlit**: Web application framework for Python.
- **OpenCV**: Computer vision library for image processing.
- **NumPy**: Library for numerical operations in Python.
- **Imutils**: Utility functions for OpenCV.
- **EasyOCR**: Optical Character Recognition (OCR) library.
- **Pillow**: Python Imaging Library (PIL) fork for image processing.
