# Diabetic-Retinopathy-Detection

### What is Diabetic Retinopathy?
- Complication of diabetes affecting the retina due to prolonged high blood sugar levels.
- Early detection and treatment are crucial for preserving vision.
- Regular monitoring and management of diabetes help prevent and address the condition.

### Project Overview
- **Processes:**
  - Image Preprocessing
  - Edge Detection
  - Feature Formation
  - Model Development
- **Dataset:**
  - 3662 images (224x224 size) classified into 5 classes:
    - 0: No DR
    - 1: Mild
    - 2: Moderate
    - 3: Severe
    - 4: Proliferate
  - Source: APTOS Dataset

### Image Processing Steps
1. **RGB to Grayscale and Histogram Equalization:**
   - Simplifies algorithms, reduces memory usage and enhances contrast.
   - Histogram equalization adjusts pixel intensity distribution for better performance in edge detection and feature extraction tasks.

2. **Wavelet Transformation:**
   - Analyzes and processes signals by decomposing them into components at different scales.
   - Uses Haar Wavelet, a simple wavelet function for image transformation.
   - Wavelet transformation compresses the image and reduces computational complexity.
   - Inverse Wavelet Transform reconstructs the original image from wavelet coefficients.

### Edge Detection Techniques
1. **Pixel Feature Extraction:**
2. **Edge Detection Operators:**
   - **Prewitt Filter:** Emphasizes intensity changes along horizontal and vertical directions.
   - **Sobel Filter:** Highlights intensity changes along horizontal, vertical, and diagonal directions.
   - **Canny Edge:** Multi-stage algorithm for precise edge detection, involving Gaussian smoothing, gradient calculation, non-maximum suppression, and hysteresis.

### Disease Detection
- **Machine Learning Models Used:**
  - Logistic Regression
  - K Neighbors Classifier
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Classifier (RBF, Poly)

### Results and Conclusion
- The project presents the application of image processing and machine learning techniques for detecting diabetic retinopathy.
- The detailed steps in image preprocessing, edge detection, and feature extraction lead to effective model development and disease detection.
