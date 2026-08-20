# Assignment 3 — Feature Extraction and Image Processing

This repository contains the Python/OpenCV implementation of **Assignment 3** covering feature extraction, edge detection, texture analysis, image transformations, local feature descriptors, and image similarity analysis.

## Experiments

### 1. Feature Extraction and Edge Detection

* Feature extraction using SIFT
* Sobel edge detection
* Prewitt edge detection
* Canny edge detection
* Edge comparison

### 2. Edge Detection Performance Analysis

* Gaussian noise analysis
* Salt-and-pepper noise analysis
* Sobel, Prewitt, and Canny comparison
* Edge continuity
* False edge rate
* Processing time

### 3. Gabor Filter and Texture Feature Extraction

* Multiple Gabor orientations
* Multiple Gabor frequencies
* Texture response analysis
* Mean, standard deviation, energy, and entropy

### 4. Discrete Wavelet Transform

* 2-D Haar DWT
* Approximation coefficients
* Horizontal detail
* Vertical detail
* Diagonal detail
* Inverse DWT reconstruction

### 5. Line, Corner and Hough Transform Detection

* Canny edge detection
* Probabilistic Hough Line Transform
* Harris corner detection
* Hough Circle Transform

### 6. Orientation Histogram and Shape Features

* Gradient magnitude
* Gradient orientation
* Orientation histogram
* Area
* Perimeter
* Centroid
* Aspect ratio
* Circularity

### 7. Local Feature Extraction Using SIFT

* SIFT keypoint detection
* SIFT descriptor extraction
* Descriptor matching
* Lowe's ratio test
* Best feature correspondences

### 8. SIFT, SURF and GLOH Analysis

* SIFT feature analysis
* SURF availability and comparison
* GLOH descriptor implementation
* Descriptor size comparison
* Feature matching analysis

### 9. Histogram, Color, Spectral and Texture Features

* Grayscale histogram
* HSV color histogram
* Fourier/spectral features
* LBP texture features
* Gabor texture features
* Combined feature vector

### 10. Feature Vector Analysis and Similarity Measures

* Feature vector extraction
* Standardization
* Euclidean distance
* Manhattan distance
* Cosine similarity
* Correlation
* Gallery image ranking

## Dataset

The notebook uses the provided `Feature_Extraction_Assignment_Image_Dataset`, containing dedicated images for the individual experiments and a `similarity_gallery` folder for Experiment 10.

## Technologies Used

* Python
* OpenCV
* OpenCV-Contrib
* NumPy
* Pandas
* Matplotlib
* SciPy
* PyWavelets
* Scikit-Image
* Scikit-Learn
* Google Colab
* Google Drive

## Output

The notebook automatically creates:

```text
Feature_Extraction_Assignment_Output/
├── 01_experiment/
├── 02_experiment/
├── 03_experiment/
├── 04_experiment/
├── 05_experiment/
├── 06_experiment/
├── 07_experiment/
├── 08_experiment/
├── 09_experiment/
└── 10_experiment/
```

Each folder contains the generated images, CSV files, feature vectors, comparison results, and analysis outputs for the corresponding experiment.

## How to Run

1. Open the notebook in Google Colab.
2. Upload or place `Feature_Extraction_Assignment_Image_Dataset` inside Google Drive.
3. Run the installation cell.
4. Mount Google Drive.
5. Execute the cells sequentially.
6. The complete output will be generated automatically in `Feature_Extraction_Assignment_Output`.

## Note

SURF availability depends on the installed OpenCV-Contrib build. The implementation checks for SURF availability so that the remaining experiments can execute without interruption.
