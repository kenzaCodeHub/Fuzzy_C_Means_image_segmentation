# Image Segmentation with Fuzzy C-Means

This project implements the **Fuzzy C-Means** clustering algorithm in Python and applies it to image segmentation:

- Grayscale images with **K = 2** clusters  
- Color (RGB) images, where each pixel is treated as a 3D vector (R, G, B)

The code allows you to:
- Load a grayscale or RGB image
- Convert and normalize pixel values
- Apply the Fuzzy C-Means algorithm
- Visualize membership maps and the segmented image (grayscale and color)

## Technologies

- Python 3
- NumPy
- Matplotlib
- OpenCV (`opencv-python`)

## Goal

The goal of this project is to compare the behavior of Fuzzy C-Means on grayscale images and on RGB images, and to visualize how the algorithm separates dark and bright regions in a galaxy image.
