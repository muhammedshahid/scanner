# Document Scanner with JavaScript

This project is a simple yet efficient **document scanner implemented in JavaScript**, leveraging image processing techniques to enhance scanned documents.

## Key Features
- **Binary Image Conversion**: Transforms the input image into a binary image for easier processing.
- **Otsu's Method**: Automatically determines the optimal threshold to separate foreground (text) from the background.
- **Gaussian Blur**: Applies a smoothing filter to reduce noise and improve the visual quality of the binary image.

## Technologies Used
- **JavaScript**: For implementing all the algorithms from scratch.
- **Canvas API**: For rendering and processing image data.

## How It Works
1. **Input**: Load an image of a document (e.g., a photo or scanned copy).
2. **Binary Image Processing**: The image is converted into a binary format using Otsu's thresholding.
3. **Noise Reduction**: A Gaussian blur is applied to enhance the result, creating a cleaner and sharper scanned document effect.
4. **Output**: The processed image is displayed for download or further use.

## Use Cases
- Digitizing handwritten or printed documents.
- Creating high-quality black-and-white document scans.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/muhammedshahid/scanner-js.git
