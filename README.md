# Spatial Filtering with OpenCV

This project implements various **Spatial Filtering** techniques using the OpenCV library. It demonstrates how to manipulate digital images by applying linear and non-linear filters to enhance details or reduce noise.

## 🚀 Overview
The goal of this project is to provide a practical implementation of spatial domain filtering. By processing $3 \times 3$ or $5 \times 5$ pixel neighborhoods, the application can achieve effects like blurring, sharpening, and noise reduction.

## Key Features
* **Smoothing (Low-pass):** Includes **Gaussian Blur** and **Median Filtering** to remove salt-and-pepper noise.
* **Sharpening (High-pass):** Implements **Sobel** and **Laplacian** operators to detect edges and fine details.
* **Morphological Operations:** Includes **Erosion** and **Dilation** for structural image analysis.
* **Custom Kernels:** Support for applying user-defined convolution matrices.

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KangKang0909/Spatial-Filtering-OpenCV
   cd Spatial-Filtering-OpenCV
   ```

2. **Install dependencies:**
   Ensure you have a C++ compiler and OpenCV installed. For Python users:
   ```bash
   pip install opencv-python numpy matplotlib
   ```

## 📁 Project Structure
* `main.cpp` (or `.py`): The primary execution script containing the filtering logic.
* `filters/`: Directory containing specific implementations of spatial masks.
* `images/`: Folder for sample input images and processed output results.
