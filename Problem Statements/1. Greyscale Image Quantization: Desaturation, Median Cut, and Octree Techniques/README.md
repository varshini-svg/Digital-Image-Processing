# Greyscale Image Quantisation

### Overview
This project demonstrates color quantization and non-uniform spatial quantization techniques in digital image processing. It uses K-Means clustering for color reduction and a QuadTree algorithm for adaptive block-based spatial quantization. The notebook also generates multiple graphs to visualize distortions, cluster centers, histograms, block size distributions, and variance distributions.

### Features

1. Color Quantization (K-Means) 
- Elbow curve to determine optimal number of clusters.
- Quantized images for different values of K (4, 8, 16).
- Cluster center RGB bar plots.
- Pixel intensity histograms for original image channels.

2. Non-Uniform Spatial Quantization (QuadTree)
• 	Adaptive block splitting based on variance threshold.
• 	Reconstructed image using average block colors.
• 	Graphs showing block size distribution and variance distribution.
• 	Automated Output Saving
• 	All images and graphs are saved to a dedicated folder 
