\\ DIP Task 12 – Image Thresholding and Segmentation

Overview
This project demonstrates fundamental image processing techniques used in Digital Image Processing (DIP). The main goal is to perform different thresholding and segmentation methods on an image using Python in Google Colab and visualize the results in a single figure.

Objectives
To upload and process an image interactively in Google Colab
To convert a color image into grayscale
To apply different thresholding techniques
To perform color-based image segmentation
To visualize and compare all results clearly

Tools & Libraries Used
Python
OpenCV (cv2)
NumPy
Matplotlib
Google Colab

Methods Implemented
1. Grayscale Conversion
The uploaded image is converted from RGB format to grayscale to simplify processing for thresholding operations.

2. Thresholding Techniques
The following binary image generation techniques are applied:
Global Thresholding
Otsu’s Thresholding
Adaptive Thresholding
These methods separate foreground and background pixels based on intensity values.

3. Color-Based Segmentation
To segment the image based on color information:
K-Means Clustering is applied with different cluster values:
k = 2
k = 3
k = 4

Mean Shift Segmentation is used to smooth the image and group similar color regions.

Results Visualization
All outputs are displayed using Matplotlib in a single figure containing multiple subplots, including:
Original image
Grayscale image
Thresholded images
K-Means segmented images
Mean-shift segmented image
Grayscale images are shown in gray, while color images are displayed in RGB format.

How to Run
Open Google Colab
Copy and paste the provided Python script into a notebook cell
Run the cell and upload an image when prompted
View the segmentation and thresholding results

Applications
Medical image analysis
Object detection
Image segmentation tasks
Computer vision preprocessing

Conclusion
This task highlights the effectiveness of various thresholding and segmentation techniques in digital image processing. By comparing different methods, we can understand how each technique performs under varying image conditions.
