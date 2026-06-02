# Smart Whiteboard / Document Scanner using Image Stitching

## Project Overview

This project presents a Computer Vision-based Smart Whiteboard / Document Scanner that combines multiple overlapping images into a single high-resolution document using image stitching techniques. The system is designed to digitize large whiteboards, classroom notes, posters, maps, and documents that cannot be captured completely in a single photograph.

The project implements classical Computer Vision techniques including ORB feature detection, feature matching using BFMatcher, homography estimation using RANSAC, perspective transformation, and image blending to generate a seamless stitched output.

---

## Problem Statement

Large whiteboards and documents often require multiple photographs for complete coverage. Manual merging of these images is time-consuming and error-prone. This project automates the process by detecting overlapping regions, aligning images, and generating a single readable document image.

---

## Features

- ORB Feature Detection
- BFMatcher Feature Matching
- RANSAC Homography Estimation
- Perspective Warping
- Image Blending
- Automatic Image Stitching
- High-Resolution Output Generation
- Google Colab Compatible

---

## Technology Stack

### Programming Language
- Python

### Libraries
- OpenCV
- NumPy
- Matplotlib

### Development Environment
- Google Colab
- Jupyter Notebook
- Visual Studio Code

---

## Workflow

Input Images
↓
Image Preprocessing
↓
ORB Feature Detection
↓
Descriptor Extraction
↓
Feature Matching
↓
RANSAC Homography Estimation
↓
Perspective Transformation
↓
Image Blending
↓
Final Stitched Output

---

## Methodology

### Step 1: Image Acquisition
Multiple overlapping images are captured from a whiteboard or document.

### Step 2: Image Preprocessing
Images are resized and converted to grayscale for efficient processing.

### Step 3: Feature Detection
ORB is used to detect keypoints and extract descriptors.

### Step 4: Feature Matching
BFMatcher identifies corresponding features between overlapping images.

### Step 5: Homography Estimation
RANSAC removes outliers and computes a robust homography matrix.

### Step 6: Perspective Warping
Images are transformed into a common coordinate system.

### Step 7: Image Stitching
Aligned images are blended together to create a seamless output.

---

## Results

The proposed system successfully combines multiple overlapping images into a single high-resolution document. By utilizing ORB feature detection, feature matching, homography estimation, and image warping, the project demonstrates the practical application of Computer Vision techniques for document digitization and image alignment.

## Future Work

Potential improvements include:

- Deep Learning-based feature matching
- OCR integration for text extraction
- Mobile application development
- Cloud-based deployment
- Real-time image stitching
- Automatic image enhancement and noise removal

## Contact

Mahnoor Yasir

GitHub: https://github.com/mahnoor-yasir

LinkedIn: https://www.linkedin.com/in/mahnoor-yasir

Email: mahnooryasir04@gmail.com

## Acknowledgements

This project was developed as part of the Computer Vision course and is based on concepts from:

- Richard Szeliski, *Computer Vision: Algorithms and Applications*
- Richard Hartley and Andrew Zisserman, *Multiple View Geometry in Computer Vision*
- David Forsyth and Jean Ponce, *Computer Vision: A Modern Approach*
- OpenCV Documentation
