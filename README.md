# Document Scanner with JavaScript

This project is a simple yet efficient **document scanner implemented in JavaScript**, leveraging image processing techniques to enhance scanned documents.

## Live Demo
- https://muhammedshahid.github.io/scanner/

## Key Features
- **Binary Image Conversion**: Transforms the input image into a binary image for easier processing.
- **Otsu's Method**: Automatically determines the optimal threshold to separate foreground (text) from the background.
- **Gaussian Blur**: Applies a smoothing filter to reduce noise and improve the visual quality of the binary image.
- **Median Blur**: Reduces noise by replacing each pixel's value with the median of its neighbors, preserving edges while improving visual quality.
- **No Upload**: Truly leverage the power of client side processing.

## Technologies Used
- **JavaScript**: For implementing all the algorithms from scratch.
- **Canvas API**: For rendering and processing image data.

## How It Works
1. **Input**: Load an image of a document (e.g., a photo or scanned copy).
2. **Binary Image Processing**: The image is converted into a binary format using Otsu's thresholding.
3. **Noise Reduction**: Gaussian blur and Median Blur is applied separately to enhance the result, creating a cleaner and sharper scanned document effect.
4. **Output**: The processed image is displayed for download or further use.

## Use Cases
- Digitizing handwritten or printed documents.
- Creating high-quality black-and-white document scans.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/muhammedshahid/scanner-js.git
## How to Use
1. Open `index.html` in a browser.
2. Upload an image and view the processed output.

## Future Improvements
- Add real-time scanning via webcam integration.
- Include additional filters for color document enhancement.
- Support for saving output in multiple formats (e.g., PDF, PNG).

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

