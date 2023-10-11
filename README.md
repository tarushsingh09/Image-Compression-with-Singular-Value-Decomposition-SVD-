# Image Compression with Singular Value Decomposition SVD

# Exploring Image Compression with Singular Value Decomposition (SVD)
# Overview:
This Python script, authored by Tarush Singh (E21CSEU0974), is part of the "Intelligent Model Design" lab assignment (CSET-225, Lab 8). The primary objective of this assignment is to introduce students to the concept of Singular Value Decomposition (SVD) and its practical application in image compression and reconstruction.

# -> Key Features:

 1) Image Loading: The script begins by loading an example image (the camera image) from the scikit-image library.
 2) Singular Value Decomposition (SVD): The core functionality is implemented through the svd_compression function, which applies SVD to compress the input image based on a specified compression level (parameter k).
 3) Image Display: The original and compressed images are displayed using the matplotlib library to visually compare the results.
 4) Color Image Compression: The script extends its functionality to handle color images. The svd_compression_color function performs SVD on individual color channels for RGB images.
 5) Batch Compression: The script demonstrates the compression of five sample images, displaying both the original and compressed versions for visual inspection.

# Instructions:
Run the script to observe the image compression and reconstruction process.
Experiment with different values of the compression parameter k to observe its impact on image quality and file size.
Understand the implementation details of SVD for both grayscale and color images.
This educational resource serves as a hands-on introduction to SVD and its application in image processing. Feel free to explore and modify the code for deeper insights into the concepts discussed.
