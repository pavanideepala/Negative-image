# Generate Negative Images using OpenCV in Python

This project demonstrates how to generate negative images from an input image using the OpenCV library in Python. A negative image is created by inverting the color of each pixel.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.x**
- **OpenCV**: Install it using pip:

pip install opencv-python
Getting Started

Step 1: Clone the repository
git clone https://github.com/your-username/negative-image-generator.git
cd negative-image-generator


Step 2: Install the required dependencies
pip install -r requirements.txt


Step 3: Run the script
Place your input image in the project directory and run the following Python script:
python generate_negative.py --input <input_image> --output <output_image>

Step 4: Output
The script will save the negative image to the specified output path.

Customization
You can modify the script to handle various image formats (e.g., PNG, BMP, TIFF).
Optionally, add additional image transformations like grayscale conversion before generating the negative.
