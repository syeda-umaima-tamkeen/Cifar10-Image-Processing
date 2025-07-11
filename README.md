# Image Processing Tasks Using OpenCV

**Project by:** Syeda Umaima Tamkeen

## 📝 Summary

This project demonstrates the implementation of various **image processing techniques** using **OpenCV**. The tasks range from basic operations like grayscale conversion and color channel separation to advanced processes such as edge detection using the Canny algorithm and Gaussian blurring. The goal was to understand fundamental image processing functions and visualize their effects on images.

---

## 🔍 Key Steps

### 1. Gray-scaling and Color Channel Separation
- Converted color images to grayscale using `cv2.cvtColor()`.
- Separated red, green, and blue channels using `cv2.split()`.
- Visualized results with Matplotlib.

### 2. Image Translation
- Shifted images along x-axis (100 pixels) and y-axis (50 pixels) using a translation matrix.
- Applied translation with `cv2.warpAffine()`.

### 3. Image Rotation
- Rotated images by 90°, 180°, 270°, and 360° using `cv2.getRotationMatrix2D()` and `cv2.warpAffine()`.

### 4. Scaling and Resizing
- Scaled images to 15% of original size (linear interpolation).
- Enlarged images to twice original size (cubic interpolation).
- Resized to fixed dimensions (200x400 pixels) using area interpolation.

### 5. Gaussian Blur
- Applied Gaussian blur with kernel size (15, 15) using `cv2.GaussianBlur()`.

### 6. Brightness and Contrast Adjustment
- Modified brightness and contrast using `cv2.convertScaleAbs()` with alpha=1.5 and beta=50.

### 7. Cropping
- Cropped a 200x200 pixel region starting at coordinates (50, 50) using numpy slicing.

### 8. Drawing a Circle
- Drew a green circle at the image center with radius 50 pixels using `cv2.circle()`.

### 9. Canny Edge Detection
- Applied Canny edge detection with thresholds 100 and 200 via `cv2.Canny()`.

### 10. Smart Surveillance System Pipeline
- Combined contrast/brightness adjustment, Gaussian blur, and Canny edge detection to simulate a surveillance image processing pipeline.

### 11. Histogram Analysis
- Computed and plotted histograms for grayscale, blue, and green channels using `cv2.calcHist()` and Matplotlib.

### 12. Linear Spatial Filtering (Sobel Edge Detection)
- Applied Sobel filter using `cv2.filter2D()` with a custom kernel to detect edges.

---

## ✅ Results

The project successfully demonstrated:

- Grayscale conversion and color channel separation.
- Image translation, rotation, scaling, and resizing.
- Noise reduction with Gaussian blur.
- Effective edge detection via Canny and Sobel filters.
- Image enhancement through brightness and contrast adjustment.
- Histogram analysis for image intensity distribution.
- Construction of a basic image processing pipeline for surveillance.

Visualizations clearly showed the effects of each operation on the input images.

---

## 📌 Conclusion

This project highlights the versatility of **OpenCV** for fundamental image processing tasks. It lays a solid foundation for advanced computer vision applications such as image classification, object detection, and smart surveillance. The implemented techniques confirm OpenCV’s strength as a practical tool for real-world image analysis and enhancement.


